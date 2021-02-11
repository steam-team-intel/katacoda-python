Lists store data of any type, are ordered and can be modified.

An empty list can be created using the following statement:

`my_list = []
print(my_list)`{{copy}}

This statement creates a list of integers:

`my_list = [1, 2, 3, 4]
print(my_list)`{{copy}}

And this statement creates a mixed data list:

`my_list = ['hello', 9.6, 24, 'goodbye']
print(my_list)`{{copy}}

By being ordered, we can obtain and modify elements by position, through what we call their index:

`my_list = ['hello', 9.6, 24, 'goodbye']
print(my_list[0])
my_list[0] = 'hi'
print(my_list)`{{copy}}

There are several methods for managing lists. For example, with len() you get the size of a list:

`len(my_list)`{{copy}}

And the insert() method inserts an element at a given position in the list:

`my_list.insert(0,'hola')
print(my_list)`{{copy}}

Whereas append() inserts an element at the end. Try inserting an element of any type at the end of my_list.

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}
