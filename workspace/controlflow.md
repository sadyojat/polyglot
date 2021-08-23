Each language supports different control flows. 

### Swift
---

The following control flows are supported in swift
1. `for-in` - to iterate over a sequence
```swift
for num in nums {
    // perform action
}

// While iterating thru a dictionary, the order is not guaranteed
for (key, value) in someDict {
    // perform action
}

// using `.enumerated()` will return the index and the value of each element in the array
for (idx, value) in someArray.enumerated() {
    // perform action
}

for (idx, (key, value)) in someDict.enumerated() {
    // perform action
}
```

2. `while` - evaluate the condition at the start of each loop
```swift
while ( condition ) {
    // perform action
}
```
3. `repeat-while` - evaluate the condition at the end of each loop
```swift
repeat {
    // perform action
} while(condition) // execute the loop atleast once before validating the condition
```

### Go
---

Go on the other hand supports a limited control flow set. There is no `while` loop construct and for is overloaded here to perform while like behavior. The following flavors are supported

`for loop`
```Go
for k := 1; k<=10 ; k++ {
    // perform something
}

// This is similar to while loop
for k <= 10  {

}

// a range is similar to .enumerated in swift
for idx, value := range someArray {
    // do something
}
```

### Kotlin
---

Kotlin and swift support similar constructs

1. `for-in loop`
```kotlin
for (i in 10...1000) {
    // do something
}
```

2. `while loop`
```kotlin
while (someCondition) {
    // do something
}
```

3. `do-while loop`
```kotlin
do {
    // do something
} while (condition)
```


