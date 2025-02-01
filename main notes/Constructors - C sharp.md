31-01-25
02:09 pm

``` C#
class Person

{

    string name;

        string gender;

        int age;

        string job;

  

    public Person() // This is the Constructor

    {

        gender = "male";

        age = 150;

        job = "Harbinger of death";

    }

  

    public void Greet()

    {

        Console.Write($"Hi {name} how is you'r {job} going?");

    }

  

    static void Main()

    {

        Person Bob = new();

        Bob.name = "Bob";

        Bob.Greet();

    }

}
```

- Consturctors are special methods that are used to assign default values to the fields(variables in the class). 
- the constructor name must match the class name, and it cannot have a return type.
- Since constuctors are just methods they can also accept parameters and can also be overloaded.