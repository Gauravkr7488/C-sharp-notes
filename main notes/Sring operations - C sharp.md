26-01-25
09:52 pm

### Escape Sequence

\n -> new line
\t -> inserts a tab
\u -> for unicodes
\\\ -> to get the '\\' in the string

### Verbatim

use @ before the double qoutes to use the verbatim meaning to get exactly what you have entered.
eg-> 

``` c#
Console.WriteLine(@"This is a
				  cat  /hehehe")
```

this will print like 

```
This is a 
cat /hehehe
```

### String interpolation

So when you need to write using both hardcoded string and constant you do this :-

``` C#
string message = greeting + " " + firstName + "!";
```
 which will give you the output :-

```
hi gaurav!
```

So instead you can do this :-

``` C#
string message = $"{greeting} {firstName}!";
```
this will give the same output and its called strind interpolation. 