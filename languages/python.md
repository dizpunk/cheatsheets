## Comments

```
# Single line comments
```
```
""" Multiline strings, often used
    as documentation.
"""
```

<br>

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

<br>

## Data Structures

__Lists__ - Hold an ordered and changeable collection of items. Lists allow duplicate values.
```
list = []
list = ["A", 5, 6, True]
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

<br>

__Tuples__ -  Hold an ordered and immutable collection of items.
```
tuple = (1, 2, 3)
tup[0]      # => 1
tup[0] = 3  # Raises a TypeError
```

Most of the list operations are valid for tuples too

<br>


__Dictionaries__ - Store keys to values mappings. Dictionary items are ordered, changeable and does not allow duplicates.
```
dictionary = {}
dictionary = {"one": 1, "two": 2, "three": 3}
```

Keys for dictionaries have to be immutable types.
Immutable types include ints, floats, strings, tuples.

Look up values using corresponding key
```
dictionary["one"]       # => 1
dictionary.get("one")   # => 1
```

Get all keys / values
```
list(dictionary.keys())  # => ["one", "two", "three"]
list(dictionary.values())  # => [1, 2, 3]
```

Check for existence of keys
```
"one" in dictionary  # => True
1 in dictionary      # => False
```

Adding an element
```
dictionary["four"] = 4
dictionary.update({"four":4})
```

Remove keys
```
del dictionary["one"]
```

<br>

__Sets__ - Hold an unordered, unchangeable collection of items. Sets do not allow duplicate values.
```
set = set()
set = {1, 2, 2, 3, 3, 4}  # some_set is now {1, 2, 3, 4}
```

Elements of a set have to be immutable.

Add items
```
set.add(5)  # set is now {1, 2, 3, 4, 5}
set.add(5)  # remains as before {1, 2, 3, 4, 5}
```

Intersection (__&__), union (__|__), difference (__-__), symmetric difference (__^__), superset
```
other_set = {3, 4, 5, 6}
set & other_set  # => {3, 4, 5}

filled_set | other_set  # => {1, 2, 3, 4, 5, 6}

{1, 2, 3, 4} - {2, 3, 5}  # => {1, 4}

{1, 2, 3, 4} ^ {2, 3, 5}  # => {1, 4, 5}

{1, 2} >= {1, 2, 3} # => False
{1, 2} <= {1, 2, 3} # => True
```

Check for existence
```
2 in set   # => True
10 in set  # => False
```
