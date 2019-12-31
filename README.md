# PythonTasks

T1. Write a function that removes all duplicates from list. Exmaple:
```python
>>> remove_duplicates([2, 1, 2, 1, 5, 0, 4, 0, 0, 2])
[2, 1, 5, 0, 4]
```
T1.1. Returning list is not obligatory.
T1.2. Final list should not be sorted (preserve original object sequence).

T2. Having nested lists write a function `flatten` that composes one flat list from all nested lists. 
The depth of nesting can be random. Example:
```python
>>> l = [1, [2, 3], [4, [5], 6]]
>>> flatten(l)
[1, 2, 3, 4, 5, 6]
```

T3. Write a function that returns reduced list. Sibling elements in this list are compressed into one value. Example:
```python
>>> getReduced([1, 1, 2, 3, 3])
[1, 2, 3]
```
T3*. Write same function, but pass a parameter to control tolerance. Example:
```python
>>> getReduced([1.1, 0.9, 1, 3, 3.3], tolerance=0.2)
[1.1, 3, 3.3]
```

T4. Having a dict with multiple entries, write a function that deletes all entries except one that is defined by user. Example:
```python
>>> d = {1:1, 2:2, 3:3}
>>> new_d = delete_all_entries_from_dict_except_one(d, 1)
>>> new_d
{1: 1}
```

T5. Think about how to implement `switch`-`case` statement using python dict, the alternative way to use `if`-`elif`-`else`.

T6. Given a value `0b1100`. Write a function that shifts the given value to the left, takes a most left shifted bit and adds it to the right. Number of bits needs to be passed. Example:
```python
>>> value = '0b1100'
>>> shift_left(value, 4)
'0b1001'
```

T7. Write a function that converts hex representation of RGB color to integers and visa versa. Example:
```python
>>> convertToInt('#ffcc22')
(255, 204, 34)
>>> convertToHex((255, 204, 34))
'#ffcc22'
```

T8. Implement factorial function.

T9. Print first 10 elements of the Fibonacci sequence starting from (0, 1). Implement a function.

T10. Implement `Version` class that can be used as module version checker. Here are some tests:
```python
>>> v1 = Version(major=1, minor=2, build=3)
>>> v2 = Version(1, 2, 3)
>>> v3 = Version(1, 2, 4)
>>> v1 == v2
True
>>> v1 < v3
True
>>> v2 > v3
False
```
