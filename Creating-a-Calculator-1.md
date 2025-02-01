## Creating a simple Calculator
<br>

For this demo, we will be creating a simmple calculator. below is the code:

```
/// Creating the variable number1 and number2 to store the user input.
number1 = input(Enter the first number: )
number2 = input(Enter the second number: )

/// Combined the user input that is stored on the variable number1 and number2.
ans = int(number1) + int(number2)

///  Output the result from the ans variable.
print(ans)

```

<br>

The ``` /// ``` is used to write a comment or a description. We can also use ```#``` alternatively.
<br>

The variables ```number1``` and ```number2``` is used to store the the user input.
<br>

The ```ans``` variable is represents the combined output of the stored input in the ```number1``` and ```number2``` variables.
<br>

The ```int()``` function is use in order to convert the from the user input from ```number1``` and ```number2``` into a whole number.
<br>

The ```print(result)``` will then print the result of ```ans```.
<br>
<br>

***Question:*** [string](https://docs.python.org/3/library/string.html)? but we input a number? shouldn't that be enough?

***Answer:*** When we get an ```input()``` from a user, by default, python will just convert it as a ```string``` that is why we use ```int()``` function.
<br>
<br>

***Question:*** What if we input a decimal number? will it still work?
<br>

***Answer:*** It will output an error. That is because the ```int()``` function only look and convert a string into a whole number. In order to input a decimal number, we will be using the [float()](https://docs.python.org/3/library/functions.html#float) function.
<br>
<br>

***Question:*** What if we want to use both whole and decimal numbers?
<br>

***Answer:*** To use both, we can use the [eval()](https://docs.python.org/3/library/functions.html#eval)function. As the name suggest, it evaluates the inputted value and also supports string values.










