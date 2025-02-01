31-01-25
09:08 pm

- The `try` statement allows you to define a block of code to be tested for errors while it is being executed.

- The `catch` statement allows you to define a block of code to be executed, if an error occurs in the try block.
- The `try` and `catch` keywords come in pairs:
```C#
try 
{
  //  Block of code to try
}
catch (Exception e)
{
  //  Block of code to handle errors
}
``` 

- The `finally` statement lets you execute code, after `try...catch`, regardless of the result.
```C#
try
{
  int[] myNumbers = {1, 2, 3};
  Console.WriteLine(myNumbers[10]);
}
catch (Exception e)
{
  Console.WriteLine("Something went wrong.");
}
finally
{
  Console.WriteLine("The 'try catch' is finished.");
}
```

- The `throw` statement allows you to create a custom error.The `throw` statement is used together with an exception class. There are many exception classes available in C#: `ArithmeticException`, `FileNotFoundException`, `IndexOutOfRangeException`, `TimeOutException`, etc.
```C# 
static void checkAge(int age)
{
  if (age < 18)
  {
    throw new ArithmeticException("Access denied - You must be at least 18 years old.");
  }
  else
  {
    Console.WriteLine("Access granted - You are old enough!");
  }
}

static void Main(string[] args)
{
  checkAge(15);
}
```
