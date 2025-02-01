27-01-25
10:50 am

### Class

Class is a blueprint which is used to create an object. In a class Methods(behavior) and properties(data) are mentioned. 

``` kotlin
class ClassName {
	// Properties and methods go here
}
```

### Properties

Properties are basically data that is in the class you can also say that these are just variables.

### Methods

- These are the functions that the class consists most of the time they consist the properties and do something with them.
- Should be named in Pascel case. `LikeThis()`.
- You call the method preety much the same way as a function just write `MethodName()`.
- To make method with optional parameter declear a default value for the parameter.

### Object

An Instance of a class is called an object.
eg- 

1. Kotlin - 
``` kotlin
class person {
	var name: String,
	var age: Int,
	var job: String
}

fun main() {
	val Bob = person(name = "Bob", age = 40, job = "Ultra Marine")
}
```
here we make a Bob object with the help of person class. 

2. C# -
``` C#
// IDK how to make class in C# so lets assume its a class person

Person Bob = new Person(name = "Bob", age = 40, job = "Ultra Marine")
```
**new** keyword is used whenever we are making a new object. 

