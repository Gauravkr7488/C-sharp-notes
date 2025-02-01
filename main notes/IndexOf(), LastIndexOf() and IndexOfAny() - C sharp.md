29-01-25
08:52 pm

```C#
string name = "gaurav";

char[] chars = name.ToCharArray();

int position = name.IndexOf('a'); // Learning about IndexOf()
```

- `IndexOf()` is a method of class `string`.
- `IndexOf()` takes in a characte takes a character as a parameter and will return the index of its first instance. 
- `LastIndexOf()` works the same way but gives out the last instance of the character. 
- `IndexOfAny()` reports the index of the first occurrence of any character in a supplied array of characters. The method returns **-1** if all characters in the array of characters are not found