28-01-25
01:13 pm

``` C#
int A = 5;

do

{

    Console.WriteLine($"This is the do - while loop speaking \n The value of A is {A}, So A is less than 5");

    A++;

} while (A < 5);

  

while (A < 5)

{

    Console.WriteLine($"This is the while loop speaking \nThe value of A is {A}, So A is less than 5");

    A++;

}
```

The loop with the `do` executed before it checks whats the `while` condition is and because of that even if the condition may not meet initialy as in the given code the `do` loop will work once while the `while` loop will not. 