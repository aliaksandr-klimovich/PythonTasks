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
