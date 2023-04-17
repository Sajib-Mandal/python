## isupper():	
Returns True if all characters in the string are upper case.
```python
a = "Hello World!"
b = "hello 123"
c = "MY NAME IS PETER"

print(a.isupper()) # False
print(b.isupper()) # False
print(c.isupper()) # True
```
```python
def isUpper(s):
    count = 0
    for i in s:
        if i.isupper():
            count += 1
    return count

print(isUpper("Sajib Mandal")) # 2: Total 2 uppercase letter `SM`
```
