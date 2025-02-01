## Creating a simple Calculator
<br>

For this demo, we will be creating a simmple calculator. below is the code:

```
/// Creating the variable number1 and number2 to store the user input
number1 = input(Enter the first number: )
number2 = input(Enter the second number: )

/// Combined the user input that is stored on the variable number1 and number2
ans = int(number1 + number2)

///  Output the answer from the result variable
print(ans)

```

<br>

The variable ```number1``` and ```number2``` is used to store the the user input.
<br>

The ```ans``` variable is represents the combined output of the stored input in the ```number1``` and ```number2``` variables.
<br>

The ```int()``` is use to convert string into number.
<br>

The ```print(result)``` will then print the result of ```ans```.
<br>
<br>

Question: [string](https://docs.python.org/3/library/string.html)? but we input a number. shouldn't that be enough?

Answer: When we get an ```input()``` from a user, by default, python will just convert it as a ```string``` that is why we use ```int()```.








