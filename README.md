# PythonTasks

## List

L1. Having nested lists write a function `flatten` that composes one flat list from all nested lists. 
The depth of nesting can be random. Example:
```python
>>> l = [1, [2, 3], [4, [5], 6]]
>>> flatten(l)
[1, 2, 3, 4, 5, 6]
```

## Dict

D1. Having a dict with multiple entries, write a function that deletes all entries except one that is defined by user. Example:
```python
>>> d = {1:1, 2:2, 3:3}
>>> new_d = delete_all_entries_from_dict_except_one(d, 1)
>>> new_d
{1: 1}
```

## Bit logic

BL1. Given a value `0b1000`. Write a function that shifts the given value to the left, takes a most left shifted bit and adds it to the right. Example:
```python
>>> value = '0b1100'
>>> shift_left(value)
'0b1001'
```
