## While loop
While loops execute a piece of code in a loop as long as a premise is true.

Each execution of that piece of code is called an iteration. The condition is checked at the beginning of each iteration, to determine if the loop should be broken.
```python
x = 0
while x<5:
    print(x)
    x += 1
```{{copy}}

```python
students = ['Andrew', 'Ana', 'July'] #list of students
while students: #as long as there are items in the list
    print(students.pop(-1)) #print a student name and remove it from the list
```{{copy}}

***PD: *** We will see more about lists and their handling later.
    
Another example of while where it is clearly seen how the conditions are verified:

```python
homework = True
while homework: #Runs as long as it's true
    print('I have to do my homework')
    work = True
    if work:
        print('I start to do my homework')
        homework = False

if homework == False:
    print('I finished my homework')
```{{copy}}

## For loop

For loops run a specified number of times.

They are useful for traversing elements, that is, traversing a sequence element by element.

They use a counter to determine how many iterations they take and when they should stop. By convention, this counter is called "i".

The counter starts at 0 by default, but this can be changed:

```python
for i in range(1, 6): #counts from 1 to 5 (must be less than 6)
    print(i)
```{{copy}}

```python
for i in range(5): #counts from 0 to 4 (must be less than 5)
    print(i)
```{{copy}}

```python
for i in range(2, 20, 2): #starts at 2, it must be less than 20, increments i two by two
    print(i)
```{{copy}}

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}
