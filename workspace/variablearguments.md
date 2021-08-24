Variable arguments are flexibly sized argument lists that are commonly used in C family of languages. Functions that support the use of variable argument lists are called variadic functions.

## Swift

```swift

/* 
* In this example an arbitrary number of Doubles are taken as arguments. 
* Aggregation functions like count will operate on such arguments,  however index values do not exist. 
*/
func arithmeticMean(_ numbers: Double...) -> Double {
    var total: Double = 0

    for aNumber in numbers {
        total += aNumber
    }
    return total / Double(numbers.count)
}
```

## Golang

```golang
func arithmeticMean(nums ...int) int {
	total := 0
	for _, num := range nums {
		total += num
	}
	return total / len(nums)
}
```

## Kotlin

```kotlin
fun arithmeticMean(vararg numbers: Int) : Int {
    var total = 0

    for (number in numbers) {
        total += number
    }
    return total/numbers.count()
}
```