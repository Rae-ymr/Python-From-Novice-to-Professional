## **Lists**
#### Common Sequence Operations

##### Indexing
accessing individual element 
```
>>> greeting = 'Hello'
>>> greeting[0]
'H' 
>>> greeting[-1]
'o'
```



##### A Nifty Shortcut

```
>>> numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
>>> numbers[-3:-1]
[8, 9]
>>> numbers[-3:]
[8, 9, 10]
```
##### Longer Steps
##### Adding Sequences
##### None, Empty Lists, and Initialization
##### Membership

```
>>> permissions = 'rw'
>>> 'w' in permissions
True
```

##### Length, Minimum, and Maximum

#### Python’s Workhorse
##### The list Function
```
>>> list('Hello')
['H', 'e', 'l', 'l', 'o']

**''.join(somelist)** :To convert a list of characters such as the preceding code back to a string, you would use the
following expression
```
##### Deleting Elements
##### Assigning to Slices
```
>>> name = list('Perl')
>>> name
['P', 'e', 'r', 'l']
>>> name[2:] = list('ar')
>>> name
['P', 'e', 'a', 'r']
``` 
##### append clear count index insert pop







## **Tuples**
```
>>> 1, 2, 3
(1, 2, 3)
```





## **Strings**
```
>>>"{}, {} and {}".format("first", "second", "third")
'first, second and third'
>>> "The number is {num}".format(num=42)
'The number is 42'
>>> "{num:10}".format(num=3)
'          3'
>>> print('{0:10.2f}\n{1:10.2f}'.format(pi, -pi))
          3.14
          -3.14
>>> print('{0:10.2f}\n{1:=10.2f}'.format(pi, -pi))
          3.14
-         3.14
>>> print('{0:-.2}\n{1:-.2}'.format(pi, -pi)) 
3.1
-3.1
>>> print('{0:+.2}\n{1:+.2}'.format(pi, -pi))
+3.1
-3.1
```
##### join
```
>>> dirs = '', 'usr', 'bin', 'env'
>>> '/'.join(dirs)
'/usr/bin/env'
```













