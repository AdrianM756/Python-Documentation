## Python Conditions

[If Statement](https://docs.python.org/3/reference/compound_stmts.html#if) comprises of a piece of code that only executes when the if statement's condition is ***TRUE***. If the condition is ***FALSE***, then the condition will not be executed. In simple terms, it use to create decisions in python.
<br>

[Elif Statement](https://www.w3schools.com/python/gloss_python_elif.asp) is use to check multiple conditions in a conditional statement.
<br>

[Else Statement](https://www.w3schools.com/python/python_conditions.asp) is use to decide if the conditional statement is ***FALSE***
<br>

Here is an example using ```if```, ```elif```, and ```else``` statements:

```
num1 = int(200)
num2 = int(500)

## If num2 is greater than num1.
if num2 > num1:
    print(str(num2) +  " is greater than " + str(num1))

## If num2 and num1 is equal
elif num2 == num1:
    print(str(num2) + " is equal to " + str(num1))

## If the previous conditions was not met 
else:
    print(str(num2) + " is less than " + str(num1))
```
<br>

***result:***
```
500 is greater than 200
```
<br>





