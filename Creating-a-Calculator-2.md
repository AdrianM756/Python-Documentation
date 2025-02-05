## Creating a Calculator 2

For this demo, we will be creating a calculator which is a much better on the previous [Calculator 1](https://github.com/AdrianM756/Python-Documentation/blob/main/Creating-a-Calculator-1.md). below is the code:

```
## The variables that we are gonna be using:

## Represents the 1st number
value1 = float(input("Enter the First Digit: "))

## Represents the math operation(+, -, *, /)
operator = input("Enter the operator(+, -, *, /): ")

## Represents the 1st number
value2 = float(input("Enter the Second Digit: "))

## Condition statement

## Addition
if operator == "+":
    print(value1 + value2)

## Subtraction
elif operator == "-":
    print(value1 - value2)

## Multiplication
elif operator == "*":
    print(value1 * value2)

## Division
elif operator == "/":
    print(value1 / value2)

## For Invalid operation
else:
    print("Invalid operation")
    
```









