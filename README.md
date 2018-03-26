# PythonTasks


## List

L1. Write a function that removes all duplicates from list. Exmaple:
```python
>>> remove_duplicates([2, 1, 2, 1, 5, 0, 4, 0, 0, 2])
[2, 1, 5, 0, 4]
```
L1.1. Returning list is not obligatory.
L1.2. Final list should not be sorted (preserve original object sequence).

L2. Having nested lists write a function `flatten` that composes one flat list from all nested lists. 
The depth of nesting can be random. Example:
```python
>>> l = [1, [2, 3], [4, [5], 6]]
>>> flatten(l)
[1, 2, 3, 4, 5, 6]
```

L3. Print first 10 elements of the Fibonacci sequence starting from (0, 1).


## Dict

D1. Having a dict with multiple entries, write a function that deletes all entries except one that is defined by user. Example:
```python
>>> d = {1:1, 2:2, 3:3}
>>> new_d = delete_all_entries_from_dict_except_one(d, 1)
>>> new_d
{1: 1}
```

D2. Think about how to implement `switch`-`case` statement using python dict, the alternative way to use `if`-`elif`-`else`.


## Bitwise operations

BL1. Given a value `0b1100`. Write a function that shifts the given value to the left, takes a most left shifted bit and adds it to the right. Example:
```python
>>> value = '0b1100'
>>> shift_left(value)
'0b1001'
```

BL2. Write a function that converts hex representation of RGB color to integers and visa versa. Example:
```python
>>> convertToInt('#ffcc22')
(255, 204, 34)
>>> convertToHex((255, 204, 34))
'#ffcc22'
```


## Functions

F1. Implement factorial function.
