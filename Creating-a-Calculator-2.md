## Creating a Calculator 2

For this demo, we will be creating a calculator which is a much better on the previous [Calculator 1](https://github.com/AdrianM756/Python-Documentation/blob/main/Creating-a-Calculator-1.md). below is the code:

```
## Condition statement

while True:
## Represents the 1st number
    value1 = eval(input("Enter the First Digit: "))

## Represents the math operation(+, -, *, /)
    operator = input("Enter the operator(+, -, *, /): ")

## Represents the 1st number
    value2 = eval(input("Enter the Second Digit: "))

## Addition
    if operator == "+":
        print(value1 + value2)
        break
## Subtraction
    elif operator == "-":
        print(value1 - value2)
        break
## Multiplication
    elif operator == "*":
        print(value1 * value2)
        break
## Dividion
    elif operator == "/":
        print(value1 / value2)
        break
    else:
        print("Invalid operation")
    
```









