31-01-25
04:19 pm

```C#
class Animal

{

    public string name;

    public virtual void Attack() // added virtual here

    {

        Console.WriteLine($"{name} just bit you");

    }

}

  

class Monkey : Animal

{

    public void Greet()

    {

        Console.WriteLine($"This is {name}, he is a bad monkey");

    }

  

    public override void Attack(){ // added override here

        Console.WriteLine($"{name} just kicked you in the face.");

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

- Polymorphism basically just lets you modify the methods from the parent class in the child class.
- To apply this first you need to declear the method in the parent class as `virtual` then the method in the child class as `override`. 