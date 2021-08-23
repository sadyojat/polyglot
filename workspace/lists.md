Lists/ Arrays are collection constructs and are used to create an ordered list of elements of the same type. 

### Swift
In Swift an array can be declared using either the `Array()` struct or either by creating an inferred list in the `[]` brackets
The mutability of an array is determined by the use of `let` or `var` construct while declaring the array, `let` forces **IMMUTABILITY**

```swift
var list = Array(repeating: 0, count: 10)   // Create an array with default values
var list: [Int] = [1, 2, 3, 4, 5]
var list = [1, 2, 3, 4, 5]                  // Inferred list
var emptyList: [Int] = []()                 // initialize to an empty array. Type declaration is needed here since inference will not work here. 
```


### Go
In golang the array elements are created using the following syntax.
**By Default** All arrays are **MUTABLE** in go


```go
var list = []int{1, 2, 3, 4}
var list = {1, 2, 3, 4}
var list []int = {}
```

### Kotlin
```kotlin

val list = listOf(1, 2, 3, 4)       // IMMUTABLE list of integers
val mutableList = mutableListOf<Int>()  // Mutable list of integers. Type needs to be provided since inference will not work here.

```