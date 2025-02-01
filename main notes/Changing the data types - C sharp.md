28-01-25
02:50 pm

### Converting from one number type to another

``` C#
int myInt = (int)myDecimal;
```

You can change the data type from a number to another number type by writing the number type bfore it in small brackets. 

### Converting to String

``` C#
string myString = myNumber.ToString();
```

You can change a data type to string by using `ToString()` method.
You just need to add `.ToString()` after whatever you want to convert.
It works since the `ToString()` is a method. 

### Converting a String to a Number

``` C#
int myNumber = int.Parse(myString);
``` 

Here we are converting a string into a int but same can be done with decimal as well. 

### The Convert Class

``` C#
int myNumber = convert.ToInt(myString);
``` 

convert class has many methods use them as you may need. 
Sometimes it doesnot work so ig its best to stick with the others most of the time. 

### The TryParse method

``` C#
string input = "123";

int number;

  

if (int.TryParse(input, out number))

{

    Console.WriteLine($"Conversion succeeded! The number is {number}");

}

else

{

    Console.WriteLine("Conversion failed. The input is not a valid number.");

}
```

As you can see `TryParse` gives out a bool value and when the bool is true it also gives out an output.

``` C#
int.TryParse(input, out number)
```
This is the format. 