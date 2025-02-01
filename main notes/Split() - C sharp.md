29-01-25
07:09 pm

```C#
string pangram = "The quick brown fox jumps over the lazy dog";

  

string[] strings = pangram.Split(' ');

  

foreach (var item in strings)

{

    Console.WriteLine(item);

}
```

- It takes one parameter a character from where the string will be broken. 