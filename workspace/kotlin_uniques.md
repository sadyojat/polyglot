There are some features which are unique to kotlin over other languages. Listing those below:

### `in` statement
---

The in statement can be used to determine `membership` and iteration in kotlin. In other languages like swift, its scope is limited to pure iteration. 

```kotlin
10 in (9...100) // this will return true

for ( i in 0...100) // used for iteration
```


### `function with an expression body`
---

```kotlin
fun multiplyByTwo(x: Int): Int = x * 2

class Mouse {
    fun makeSound() = "Squeak"

    fun run() = this.makeSound()+" "+makeSound()+" "+"Running on a wheel!!!!"
}
```
