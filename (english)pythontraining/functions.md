A function is a block of code that is executed each time it is called. It is reusable code.

Data can be passed to them as parameters, and data can be returned as a result.

The following function adds two numbers:

`def sum(int1, int2):
    print(int1 + int2)`{{copy}}

By defining this function, it can be called as follows:

`sum(1,2)`{{copy}}

Try calling the function without specifying parameters and analyze the result.

Functions can have default values, that is, default parameters:

`def sum(int1=1, int2=2):
    print(int1 + int2)
    `{{copy}}

`sum()
sum(3,4)`{{copy}}

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}