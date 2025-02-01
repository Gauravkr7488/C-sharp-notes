27-01-25
03:39 pm

``` C#
string[] fruit = new string[3];

  

fruit[0] = "apple";

fruit[1] = "banana";

fruit[2] = "grape";

  

foreach (var item in fruit) // <- I am talking about this thing

{

    Console.WriteLine(item); // <- Here you can just pass the item, it will work

}
```

as you can see in the `foreach` statement a var item is declared it is because it holds the value of the whatever you have placed in the fruit at that number and the `in` is used to show which array is this whole thing is part of. 