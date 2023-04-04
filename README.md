# List
List is a collection which is ordered and changeable. Allows duplicate members.
* Creating a list: Lists can be created using square brackets [] or using the list() constructor.
```python
# Creating a list
my_list = [1, 2, 3, 4, 5]
another_list = list("hello")
print(another_list)  # ['h', 'e', 'l', 'l', 'o']
```
* Accessing elements: Elements in a list can be accessed using their index. Indexing starts at 0 for the first element, and negative indexing starts at -1 for the last element.
```python
# Accessing elements
print(my_list[0])     # Output: 1
print(my_list[-1])    # Output: 5
```
* Slicing: Slicing allows you to extract a subset of a list. It is done using the colon (:) operator.
```python
# Slicing
print(my_list[1:3])   # Output: [2, 3]
print(my_list[:3])    # Output: [1, 2, 3]
print(my_list[2:])    # Output: [3, 4, 5]
```
* Appending: You can add new elements to the end of a list using the append() method.
```python
# Appending
my_list.append(6)
print(my_list)        # Output: [1, 2, 3, 4, 5, 6]
````
* Extending: You can add multiple elements to the end of a list using the extend() method.
```python
# Extending
my_list.extend([7, 8, 9])
print(my_list)        # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9]
```
* Inserting: You can insert an element at a specific position in the list using the insert() method.
```python
# Inserting
my_list.insert(3, "inserted")
print(my_list)        # Output: [1, 2, 3, 'inserted', 4, 5, 6, 7, 8, 9]
```
* Removing: You can remove an element from a list using the remove() method.
```python
# Removing
my_list.remove("inserted")
print(my_list)        # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9]
```
* Pop: You can remove and return the last element from a list using the pop() method.
```python
# Pop
last_element = my_list.pop()
print(last_element)   # Output: 9
print(my_list)        # Output: [1, 2, 3, 4, 5, 6, 7, 8]
```
* Index: You can find the index of an element in a list using the index() method.
```python
# Index
print(my_list.index(3))  # Output: 2
```
* Count: You can count the number of occurrences of an element in a list using the count() method.
```python
# Count
print(my_list.count(2))  # Output: 1
```
* Sorting: You can sort the elements in a list using the sort() method.
```python
# Sorting
my_list.sort()
print(my_list)        # Output: [1, 2, 3, 4, 5, 6, 7, 8]
```
* Reversing: You can reverse the order of the elements in a list using the reverse() method.
```python
# Reversing
my_list.reverse()
print(my_list)        # Output: [8, 7, 6, 5, 4, 3, 2, 1]
```
* Length: You can find the number of elements in a list using the len() function.
```python
# Length
print(len(my_list))   # Output: 8
```
* Membership: You can check if an element is in a list using the in keyword.
```python
# Membership
print(2 in my_list)   # Output: True
```
* Copying: You can create a copy of a list using the copy() method or by using the slice notation.
```python
# Copying
new_list = my_list.copy()
print(new_list)       # Output: [8, 7, 6, 5, 4, 3, 2, 1]
```
