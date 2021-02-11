## if, else, elif  
Flow control tools regulate the execution of portions of code depending on different parameters or variables.

Conditionals are used to execute a piece of code if a premise is true.

```python
if (4==8): # If 4 is equal to 8
    print("I don't know math")
else: # In case 4 is not equal to 8
    print('I do know math')
```{{copy}}

Elifs work to chain several conditions and check them:

```python
num = 40
if num > 10:
    print('The number is greater than 10')
elif num < 10:
    print('The number is les than 20')
else: 
    print('The number is 10')
```{{copy}}

Using the code above, change the values of the variable "num" so that you get all three outputs.

It is also possible to nest conditionals, that is, to check some conditions within others:

```python
x=3
color='blue'

if color == 'blue':
    if x>10:
        print('x is big')
    elif x>0:
        print('x is small')
    else:
        print('x is negative')
else:
    print('The color is not blue!')
```{{copy}}

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}

