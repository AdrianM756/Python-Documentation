## function

[function](https://www.w3schools.com/python/python_functions.asp) is a collection of code which only runs when it is called.
<br>
<br>

## def()

```def()``` is used to define a function that we want to use. For example:

```
def my_function():
  print("my first function")

my_function()
```
<br>

```my_function()``` in the 1st line is the name of the function. the one that is on the last line means we want to run/execute the code.
<br>
```:``` means that all the code that is input is going be inside the function that we've created(```my_function```).
<br>

## Parameters and Arguments

**Parameters** is the variable defined within the parentheses when we declare a function. 
<br>

**Arguments** is a value that is passed to a function when it is called. It could be a variable, value or object passed to a function or method as input.
<br>

***Question:*** What is the difference between the 2?
<br>

***Answer:***

Example of an parameter:

```
### Here car is the parameter
def favorite(car = "Toyota"):
    print("my favorite car is " + car)
    
favorite()
```
<br>

Example of an argument:

```
def favorite(**cars):
    print("ny favorite car is " + cars["Japanese"])
 
 ### Here the values Mercedes, Ford, and Toyota are arguments   
favorite(Germany = "Mercedes", US = "Ford", Japanese = "Toyota")
```
<br>

## Return statements

[Return Statements](https://realpython.com/python-return-statement/) allow us to return a value back to the caller. It  consist of the ```return``` keyword followed by an optional value. For example:
<br>

```
def multiply(num):
  return 4 * num

print(multiply(4), multiply(3))
```
<br>

***result:***
```
16 12
```
<br>

In addition, adding additional code after the ```return``` keyword will not be executed because it will break us out of the function.













