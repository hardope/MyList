# My_List

Implementation of Lists data type using Linked Lists

### Usage
``` python
from list import List

# Initialize an empty list
myList = List()

# Initialize the list with values provided
myList = List([1, 2, 3])

# append Values to the list
myList.append(1)
myList.append(2)
myList.append(3)

# remove and return element from end of list
myList.pop()

# remove and return element from index of 3
myList.pop(3)

# return list length
myList.count()

# return list length
len(myList)

# return a copy of the list in this object format
myList.copy()

# return a copy of the list in default python list format
myList.to_list()

# extend a list using values from another list
myList.extend([1, 2, 3])
# extend list using the custom list object
myList.extend(otherList.copy())

# delete all elements from list
myList.clear()

print(myList)

```