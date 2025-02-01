31-01-25
03:57 pm

``` C#
class Animal

{

    public string name;

    public void Attack()

    {

        Console.WriteLine($"{name} just bit you");

    }

}

  

class Monkey : Animal // This is Inheritance process

{

    public void Greet()

    {

        Console.WriteLine($"This is {name}, he is a bad monkey");

    }

}

  

class Application

{

  

    static void Main()

    {

        Monkey Sam = new()

        {

            name = "Sam"

        };

        Sam.Greet();

        Sam.Attack();

    }

}
```

- When you want a class that has all the things (mostly) from another class that you have decleared before you use `Inheritance`.
- If you want that no class may inherient from a class you can make it `sealed`.
```C#
sealed class Treasure{
	// there is some stuff here.
}
```

- the class which is giving its things to other is called parent or base class while the other class is called child or derived class.