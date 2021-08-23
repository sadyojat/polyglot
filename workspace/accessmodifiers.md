Access modifiers help in controlling visibility.  


## Access Modifiers

### Swift
```swift
    private         // Highest Restriction - only within the enclosing declaration   
    fileprivate     // Visible only within the file where its declared
    internal        // DEFAULT -- visibility restricted to the module
    public          // Visible to all
    open            // Visible to all - ONLY for class elements and can be subclassed out of the module
```

### Go
```golang
    Go has no specified access modifiers, there are only two types of arguments - exported and non-exported.
    Exported arguments are declared with an uppercase starting character. 

    eg :: 
    var Person
    func PersonName() string { // do something }
```

### Kotlin
```kotlin
    public          // DEFAULT - accessible to everyone
    private         // Visible to only members of the same class
    protected       // Stricly limiting visibility to members of the same classes and its subclasses
    internal        // Visible within a module only
```

