# SwiftUI Arrays lesson
Using XCode Playground to learn about Arrays.<br>
![Screenshot 2024-03-16 at 7 28 43 AM](https://github.com/danielurra/Swift-UI-arrays-lesson/assets/51704179/08eb3774-bc96-4607-a8e0-7e2db8d97248)<br>
## Grab the code
```swift
// Array of constants "let"
let favFruits: [String] = ["P#0_First-Apple", "P#1 - Banana", "P#2_Last-Orange"]
// Methods applicable to both Constants and Variables

// .first
favFruits.first

// .last
favFruits.last

// [0] Index
favFruits[0]
favFruits[1]
favFruits[2
]

// count
favFruits.count

// Array of variables "var"
var favCarBrands: [String] = ["BMW", "Jeep", "Honda"]
// Methods applicable only to Variables (because of array's members changing)

// append()
var favCarBrands01: [String] = ["BMW", "Jeep", "Honda"]
favCarBrands01.append("Ferrari")
print(favCarBrands01)

// .insert()
var favCarBrands02: [String] = ["BMW", "Jeep", "Honda"]
favCarBrands02.insert("Lamborgini", at: 1)
print(favCarBrands02)

// .remove()
var favCarBrands03: [String] = ["BMW", "Jeep", "Honda"]
favCarBrands03.remove(at: 1)
print(favCarBrands03)






```
