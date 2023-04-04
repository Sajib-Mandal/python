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
# Tuple
Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
* Creating a tuple: You can create a tuple by enclosing a comma-separated sequence of elements in parentheses.
```python
# Creating a tuple
tup1 = (1, 2, 3)
tup2 = ('a', 'b', 'c')
```
* Accessing elements: You can access the elements of a tuple using their index, which starts from zero.
```python
# Accessing elements
print(tup1[0])  # Output: 1
print(tup2[2])  # Output: c
```
* Slicing: You can extract a subsequence of elements from a tuple using the slicing operator :. 
```python
# Slicing
print(tup1[1:3])  # Output: (2, 3)
```
* Concatenation: You can combine two or more tuples into a single tuple using the + operator.
```python
# Concatenation
tup3 = tup1 + tup2
print(tup3)  # Output: (1, 2, 3, 'a', 'b', 'c')
```
* Repetition: You can repeat a tuple multiple times using the * operator.
```python
# Repetition
tup4 = tup2 * 2
print(tup4)  # Output: ('a', 'b', 'c', 'a', 'b', 'c')
```
* Length: You can find the number of elements in a tuple using the len() function. 
```python
# Length
print(len(tup1))  # Output: 3
```
* Membership: You can check if an element is present in a tuple using the in operator. 
```python
# Membership
print(2 in tup1)  # Output: True
```
* Iteration: You can iterate over the elements of a tuple using a for loop.
```python
# Iteration
for item in tup2:
    print(item)  # Output: a b c
  
for item in (1, 2, 3):
    print(item)
```
* Unpacking: You can assign the elements of a tuple to individual variables using unpacking. 
```python
# Unpacking
a, b, c = tup1
print(a, b, c)  # Output: 1 2 3
```
* Sorting: You can sort the elements of a tuple using the sorted() function. 
```python
# Sorting
tup5 = (3, 2, 1)
sorted_tup5 = sorted(tup5)
print(sorted_tup5)  # Output: [1, 2, 3]
```
* Finding maximum and minimum: You can find the maximum and minimum elements of a tuple using the max() and min() functions, respectively.
```python
# Finding maximum and minimum
tup6 = (10, -5, 8, 0, 3)
print(max(tup6))  # Output: 10
print(min(tup6))  # Output: -5
```
# Set
Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
* Creating a set: You can create a set in Python by enclosing a comma-separated sequence of elements in curly braces `{}`. Alternatively, you can use the `set()` constructor to create an empty set or convert other iterable types (like lists or tuples) to a set.
```python
my_set = {1, 2, 3}
my_set = set([1, 2, 3])
```
* Adding elements to a set: You can add an element to a set using the `add()` method. The element will be added to the set if it doesn't already exist in the set.
```python
my_set.add(4)
```
* Removing elements from a set: You can remove an element from a set using the `remove()` method. If the element doesn't exist in the set, a `KeyError` will be raised.
```python
my_set.remove(3)
```
* Checking membership: You can check if an element exists in a set using the `in` operator. The operator returns `True` if the element exists in the set and `False` otherwise.
```python
print(2 in my_set)  # returns True
```
* Union of sets: You can compute the union of two or more sets using the `union()` method or the `|` operator. The union of sets contains all unique elements from all sets.
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
union_set = set1.union(set2)  # returns {1, 2, 3, 4, 5}
```
* Intersection of sets: You can compute the intersection of two or more sets using the `intersection()` method or the `&` operator. The intersection of sets contains only elements that exist in all sets.
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
intersection_set = set1.intersection(set2)  # returns {3}
```
* Difference of sets: You can compute the difference of two sets using the `difference()` method or the `-` operator. The difference of sets contains elements that exist in the first set but not in the second set.
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
difference_set = set1.difference(set2)  # returns {1, 2}
```
* Symmetric difference of sets: You can compute the symmetric difference of two sets using the `symmetric_difference()` method or the `^` operator. The symmetric difference of sets contains elements that exist in either the first or the second set, but not in both sets.
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
sym_difference_set = set1.symmetric_difference(set2)  # returns {1, 2, 4, 5}
```
* Subset and superset: You can check if a set is a subset of another set using the `issubset()` method or the `<=` operator. A set is a subset if all its elements exist in the other set. Similarly, you can check if a set is a superset of another set using the `issuperset()` method or the `>=` operator. A set is a superset if it contains all elements of the other set.
```python
set1 = {1, 2, 3}
set2 = {1, 2}
set2.issubset(set1)  # returns True
set1.issuperset(set2)  # returns True
```
* Copying a set: You can create a copy of a set using the `copy()` method. The copy is a new set with the same elements as the original set. Modifying the copy doesn't affect the original set.
```python
new_set = my_set.copy()
```
