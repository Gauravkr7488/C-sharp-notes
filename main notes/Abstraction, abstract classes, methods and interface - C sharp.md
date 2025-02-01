31-01-25
04:31 pm

- So by using abstraction you make a class that can not make an object. 

```C#

abstract class Animal 
{
  public void sleep() 
  {
    Console.WriteLine("Zzz");
  }
}

```

- Abstract method lets you declear a method without a body so its basically a blueprint that you that lets you make the real thing in the child class. 

```C#
abstract class Animal 
{
  public abstract void animalSound();
  public void sleep() 
  {
    Console.WriteLine("Zzz");
  }
}
```


- An `interface` is a completely "abstract class", which can only contain abstract methods and properties (with empty bodies)

```C# 
interface Animal 
{
  void animalSound(); // interface method (does not have a body)
  void run(); // interface method (does not have a body)
}
```

- Interfaces can contain properties and methods, but not fields.
- Interface members are by default abstract and public
- C# does not support "multiple inheritance" (a class can only inherit from one base class). However, it can be achieved with interfaces, because the class can implement multiple interfaces.
- To use multiple interface just seperate them with a comma.

```C#
class DemoClass : IFirstInterface, ISecondInterface
``` 
