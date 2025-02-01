29-01-25
09:47 am

``` C#
int[] fruits = [11, 3, 22, 0, 2];

  

Array.Resize( ref fruits, 10);

  

foreach (var item in fruits)

{

    Console.WriteLine(item);

}
```

- `Array.Resize()` resizes the array based on the number you pass after the `,` .
- If the number is greater than that of the one in array it will add `null` values and if its lower it will remove the values from the end. 