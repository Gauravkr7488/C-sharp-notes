31-01-25
12:56 pm

- `Named Arguments` - you can use the names of the arguments while using a method in order to escape the order that is in the method declearation.
eg- 
```C#
 static void makeSound(string animalOne, string animalTwo)

    {

        for (int i = 0; i < 5; i++)

        {

            Console.WriteLine($"{animalOne}");

            Console.WriteLine($"{animalTwo}");

        }

  

    }

makeSound(animalTwo: "cat", animalOne: "dog"); // Here
```

