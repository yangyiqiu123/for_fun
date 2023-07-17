# example

- ****Tuple Unpacking****

```python
# Tuple unpacking
t4 = ("John", 25, "Male")
name, age, gender = t4
print(name, age, gender)  # Output: John 25 Male
```

- ****Immutable Elements****

```python
# Immutable elements
t5 = ([1, 2], "hello")
t5[0][0] = 3  # this is allowed
t5[1] = "world"  # this will raise a TypeError
```

- ****Tuple Concatenation****

```python
# Tuple concatenation
t6 = (1, 2, 3)
t7 = (4, 5, 6)
t8 = t6 + t7
print(t8)  # Output: (1, 2, 3, 4, 5, 6)
```

- ****Tuple Methods****

```python
# Tuple methods
t9 = (1, 2, 3, 2)
print(t9.count(2))  # Output: 2
print(t9.index(3))  # Output: 2
```