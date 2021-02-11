Sets are collections of unordered and unique data, they can be modified and mathematical set operations can be applied to them.

The following code creates an assembly. Try running it several times and analyze the result obtained:

`fruit_basket = {'apple', 'orange', 'apple', 'pear', 'orange', 'banana'}
print('Basket elements: ', fruit_basket)
`{{copy}}

As you can see, repeating elements are ignored.

As in mathematical sets, it is possible to verify the membership of an element to a set:

`print('Does the basket have papaya? ', 'papaya' in fruit_basket)
`{{copy}}

Since there is no papaya, we can modify the set and add this element:
`fruit_basket.add('papaya')
print('Basket element: ', fruit_basket)
`{{copy}}

***Reminder:*** To run from console, enter the command:

`python3 testfile.py`{{copy}}
