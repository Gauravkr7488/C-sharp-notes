31-01-25
07:39 pm

-  enum is a data type that represents constants (unchangeable/read-only variables).
- enum is also a class type which only consists of enum values.
- enum values can be converted into int to perform more operations with them.
- To create an enum, use the enum keyword (instead of class or interface), and separate the enum items with a comma:

```C#
enum Height {
	High, // default value = 0
	Medium, // default value = 1
	Low // default value = 2
}
```

- They are used to make code more readable like assume you need to put a number like 32 in many places so instead of just that number you can assign it as a constant in enum. Then you will just need to type the constant's name.
- The default value of enum goes like 0, 1 , 2...
- You can assign values to enums 

```C#
enum Height {
	High = 32
}
``` 

- You can also have an enum inside a class.

```C#
class Animal {
	enum IsAlive
}
```
