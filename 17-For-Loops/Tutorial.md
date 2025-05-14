# Introduction to Loops
Sometimes a programmer wants to execute a group of statements a certain number of times. This can be done using loops. Based on this loops are further classified into following main types; 
- for loop
- while loop
---

# The for Loop
for loops can iterate over a sequence of iterable objects in python. Iterating over a sequence is nothing but iterating over strings, lists, tuples, sets and dictionaries.

### Example 1: iterating over a string

```python 
name = 'Abhishek'
for i in name:
    print(i, end=", ")
```
#### Output:

A, b, h, i, s, h, e, k,
 

### Example 2: iterating over a list

``` python 
colors = ["Red", "Green", "Blue", "Yellow"]
for x in colors:
    print(x)
```
#### Output:

Red\
Green\
Blue\
Yellow

Similarly, we can use loops for lists, sets and dictionaries.

---
## range()
What if we do not want to iterate over a sequence? What if we want to use for loop for a specific number of times?

Here, we can use the range() function.

### Example 1: we can also loop over a specific range
```python
for k in range(5):
    print(k)
```
#### Output:

0\
1\
2\
3\
4

Here, we can see that the loop starts from 0 by default and increments at each iteration.

### Example 2: range (x,n-1) -> range(start, stop)
```python
for k in range(4,9):
    print(k)
```
#### Output:

4\
5\
6\
7\
8

Here, **stop** = 9-1 = **8** 

### Example 3: range (x,n-1,m) -> range(start, stop,step)
```python
for i in range(0, 11, 2):
    print(i)  
```
#### Output:

0\
2\
4\
5\
6\
8\
10\




