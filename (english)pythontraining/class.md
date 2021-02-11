Python relies on classes to represent objects. These objects have associated attributes and methods, and some objects interact with others.

The way a class is declared is as follows:

`class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def presentation(self):
        print("Hello! My name is " + self.name)
        `{{copy}}

The __init__ method works as a constructor method of our Person class. Defines the attributes with which an object of type Person will be created.

It can also be seen that, by convention, Python methods always include a reference to themselves.

A class can be viewed as an abstract definition of an object. An ** instance **, on the other hand, is a concretion of said object.

To create instances of the Person class:

`person1 = Person('Miguel', 19)
person2 = Person('Paula', 23)`{{copy}}

Once a class has been instantiated, its methods can be called. Methods are functions associated with a class.

`person1.presentation()
person2.presentation`{{copy}}

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}
