31-01-25
01:30 pm

### Class

 Class is a blueprint which is used to create an object. In a class Methods(behavior) and properties(data) are mentioned. 

```C#
Class Car{
	Console.WriteLine("This is a Freking Kar");
}
```


### Object

An Instance of a class is called an object.

``` C#

class Person{

    string name;

    string gender;

    int age;

    string job;

  

    public void Greet(){

        Console.Write($"Hi {name}");

    }

  

    static void Main()

    {

        Person Bob = new();

        Bob.name = "Bob";

        Bob.Greet();

    }

}
```
