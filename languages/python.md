## Comments

```
# Single line comments
```
```
""" Multiline strings, often used
    as documentation.
"""
```

## Datatypes

__Numbers__
```
3
3.23
52.3E-4
```

__Boolean__
```
True
False
```

__Strings__ (immutable)
```
"This is a string."
'This is also a string.'
r"Newlines are indicated by \n" (raw string, no special processing )
```

__None__ (is an object)
```
None
```

## Data Structures

__Lists__ - Holds an ordered collection of heterogeneous items
```
list = []
elist = ["A", 5, 6, True]
```

Get length
```
len(list)
```

Check for existence
```
1 in list  # => True
```

Access a list like any array
```
list[0]
list[-1] (last element)
```

Get index of first matching item
```
list.index(value)
```

Insert, append and pop
```
list.insert(index, value)
list.append(3)    # list is now [1, 2, 4, 3]
list.pop()        # => 3 list is now [1, 2, 4]
```

Slice syntax.
```
list[start:end:step]
list[2:]
list[:3]
list[1:3]
list[::2]
```

Add lists
```
list + other_list
```

Remove element
```
del list[index]
```

Remove first occurrence of a value
```
list.remove(value)
```
