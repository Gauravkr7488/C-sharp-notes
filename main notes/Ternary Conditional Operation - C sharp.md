28-01-25
10:41 am

``` C#
condition ? expressionIfTrue : expressionIfFalse;
```

The code written above is the template for the Ternary Conditional 
I will give some examples :

``` C#
int A = 50;
int B = 10;
string C = "";

C = A > B ? "A is bigger" : "B is bigger";

Console.WriteLine(C);
```

So here you can see First we decleare where the returned value is going in in this case its `C`.
Then we write the condition `A > B` which we end with a `?`.
After the `?` we write what to return if the condition is true then be write a `:` and after this we write what will be returned if the condition is false. 


keep this in mind ==Ternary operator gives out a return type so you must use that somewhere in order to use this== 

eg : 

``` C#
int saleAmount = 1001;
// int discount = saleAmount > 1000 ? 100 : 50;

Console.WriteLine($"Discount: {(saleAmount > 1000 ? 100 : 50)}"); // here for printing in console
```
