29-01-25
09:12 am

``` C#
int[] fruits = [11, 3, 22, 0, 2];

  

Array.Clear(fruits, 0, 2);

  

foreach (var item in fruits)

{

    Console.WriteLine(item);

}
```

- To use the `Clear` we first pass the array name then pass the coordinate of the item we want to remove.
- The items whose coordintes that you have passed will be replaced if its a string then with `null` and if its a number then with `0`.