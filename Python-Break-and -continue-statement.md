## Continue

[continue](https://www.w3schools.com/python/ref_keyword_continue.asp) is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration. For example, we want to skip the number 13. It will then look like this:
```
skip = 13
for number_list in range(15):
  if number_list == skip:
    continue
  print(number_list)
```
<br>

## Break

[break](https://www.w3schools.com/python/ref_keyword_break.asp) is used to break out a for loop, or a while loop. once the condition is met, it will stop the loop. For example:

```
for double_digit in range(10):
  if double_digit >= 10 :
    break
  print(double_digit)
```
<br>


 
