31-01-25
03:40 pm

- Property is special class member that lets you get and set data for private fields(variables).

```C#
class Person

{

    private string name; // Private field

  

    public string Name // Property

    {

        get { return name; }

        set { name = value; }

    }

}

  

class Program

{

    static void Main()

    {

        Person p = new Person();

        p.Name = "Alice";  // ✅ Using property to set value

        Console.WriteLine(p.Name);  // ✅ Using property to get value

    }

}
```

- with the help of `Property` you can make a field read-only or write-only.