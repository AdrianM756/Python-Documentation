## List() Function
<br>

Generally, when we are creating normal variable in python, we usually just provide it wih one value, string, or a bolean. using the [list()](https://docs.python.org/3.13/library/stdtypes.html#list) function, we can store multiple values, strings, or booleans in one variable.
<br>

To create a list, we can use the open and close square bracket ```[]``` or the open and close parenthesis ```()```. an example would be:

```
value1 = ["20", "41", "34"]
print(value1)
```
<br>

When run, the result will be:

```
['20', '41', '34']
```
<br>

***Question:*** What if I only want to print one particular value? for example, 41 on the list?
<br>

***Answer:*** We can actually refer to a value inside a list by their index. Each one of the value inside a list has it's own particular index. Take note that the index starts in ```0```. to output value of 41, we will refer to by it's index which is ```1``` and store it in ```[]```. below is the code:

```
value1 = ["20", "41", "34"]
print(value1[1])
```
<br>

## Specifying a value via it's index position

***Question:*** What if a only want to print 41 and 34?
<br>

***Answer:*** To to that we will be using a ```:``` inside the ```[]```. see the code below as example and notice the difference:

```
value1 = ["20", "41", "34"]
print(value1[1:])
```

When run, the result will be:
```
['41', '34']
```
<br>

## Modifying value inside a list

***Question:*** Can we modify a value inside a list?
<br>

***Answer:*** Yes. Check and run the code below. On the 2nd line, we our going to type the variable containing the list (value1) and input the index position of what you want to modify (in this case, it is 34).

```
value1 = ["20", "41", "34"]
value1[2] = 57
print(value1[2])
```
When run, the result will be: ```57```
<br>

***Answer:*** Another way of modifying a list is by using the [append() method](https://www.w3schools.com/python/ref_list_append.asp). The append() method is ****always**** going to add the value on the end of the list. below is the examle code:

```
value1 = ["20", "41", "34"]

### Add the value 14 on the list.
value1.append("14")

print(value1)

```
When run, the result will be:

```
['20', '41', '34', '14']
```
<br>

## list.extend

***Question:*** What if  I want to combined a list to another list? is it possible?
<br>

***Answer:*** Yes. For that, we will use the [extend() method](https://www.w3schools.com/python/ref_list_extend.asp). For example:

```
value1 = ["20", "41", "34"]
value2 = ["roy", "james", "carl"]

### Use the extend() method to combine the value1 and value2
value1.extend(value2)

print(value1)
```
<br>

When run, the result will be:

```
['20', '41', '34', 'roy', 'james', 'carl']
```













