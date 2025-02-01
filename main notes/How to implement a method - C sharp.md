27-01-25
01:32 pm

Lets say we need to find maximum value between two values, then we can use System.Math class.

``` C#
int firstValue = 500;

int secondValue = 600;

int largerValue;

largerValue = Math.Max(firstValue, secondValue);

Console.WriteLine(largerValue);
```

in the above code we can see that we used `Math.Max` in order to find the maximum value.
So here `Math` is the class and `Max` is the method that we use and in order to use it we use a `.` between them and in `()` we passed the values.

So we can say the basic syntax to implement a method is - `Class.Method()` 