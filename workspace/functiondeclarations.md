
This document is a working draft that provides a comparative between Swift, Go & Kotlin. 


## Function Declarations


### Swift
`func functionName(args) -> returnType`
```swift
    func helloWorld(_ name : String ) -> String {
        print("Hello World \(name)")
        return "Hello World \(name)"
    }
```

### Go
`func functionName(args) returnType`

```go
func helloWorld(name string) string {
    fmt.Println("Hello World ", name)
    return fmt.Sprintf("Hello World %s", name)
}
```

### Kotlin
`fun functionName(args): returnType`

```kotlin
fun helloWorld(name: String): String {
    print("Hello World ", name)
    return "Hello World "+name
}



