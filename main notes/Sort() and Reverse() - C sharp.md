29-01-25
09:00 am

### Sort()

``` C#
string[] fruits = ["apple", "bnana", "tomato", "eggplant"];

  

Array.Sort(fruits);

  

foreach (var item in fruits)

{

    Console.WriteLine(item);

}
```

To use the sort method you just need to pass the array into the `Array.Sort()`.
It will sort all the items in the array in alphabetical or ascending order.

### Reverse()

As for reverse it works just the same but does the opposite of sort it will arrange the items in descending order, 

``` C# 
int[] fruits = [11, 3, 22, 0, 2];

  

Array.Reverse(fruits);

  

foreach (var item in fruits)

{

    Console.WriteLine(item);

}
```
