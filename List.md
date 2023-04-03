
Specify a range of consecutive indexes by specifying where to start and where to end the range in this manner
print(list[1:4]).
This will print elements from index number 
1 to 3


Note:

Indexing starts from 0.
Item on index no 
4
4 will not be printed as the end index is excluded.





Checking the elements of a list

We can check if a list contains a certain element or not using the "in" keyword along with the "if" statement.

Eg

Write a program which does the following:

You are given a list x

x in the console Compute and output if "Ram" is present in the given list. If present, then print "Ram is present"

x = ["Suraj","Gautam","Yash","Ram"] if "Ram" in x : print("Ram is present ")



Changing Item values in a list


To change the value of a specific item, you can refer to the index number of the item.

Write a program which does the following:

You are given a list 
x
x = ["India","USA","France"]
Add "Russia" in place of "France" in the list 
x
x
Once the element is replaced, print the complete list.






x = ["India","USA","France"]
x[2] = "Russia"
print(x)




 Adding list items
 
 
 To insert a list item at a specified index, we can use the insert() method which does the following

Inserts an item at the specified index
All the elements after this item are shifted to the right
Write a program which does the following:

Chef made the following list 
a
a = ["Apple","10","Cherry","Berry","32"].
Insert "45" between "10" and "Cherry" in the given list.
Output the entire list to the console


```c
a = ["Apple", "10", "Cherry", "Berry", "32"]
a.insert( 32,"45") #enter the index number 
print(a)
```


Sorting a List


List objects have a sort() method that will sort the list alphanumerically, and in ascending order by default.

A list containing only strings - for example ["b", "d", "c", "a"] when sorted will return the list ["a", "b", "c", "d"]
A list containing only numbers - for example [5, 4, 3, 2, 1] when sorted will return the list [1, 2, 3, 4, 5]
A list containing both strings and numbers - for example ["b", "d", "c", 1] will return a runtime error if we try and run the sort() operation on it
Write a program which does the following:

Consider two lists
a
a = ["Mountain","Valley","River","Sky"]
b
b = [3,7,22,1,43]
Apply the sort() operation and output the lists "a" & "b" the the console on separate lines.



```c
a = ["Mountain","Valley","River","Sky"]
b = [3,7,22,1,43]
a.sort()
b.sort()
print(a)
print(b)
```

Output
['Mountain', 'River', 'Sky', 'Valley']
[1, 3, 7, 22, 43]


Reverse Sort

If you want to sort the list in a descending order, you have to use the syntax list_name.sort(reverse=True).

Write a program which does the following:

Create two lists
a
a = ["Mountain","Valley","River","Sky"]
b
b = [3,7,22,1,43]
Apply the reverse sort() operation and output the lists 
a
a & 
b
b - sorted in a descending order - to the console.


```c
a = ["Mountain","Valley","River","Sky"]
b = [3,7,22,1,43]
b.sort(reverse = True)
a.sort(reverse = True)
print(a)
print(b)
```


Combining Lists

There are several ways to concatenate two or more lists in Python.
One of the easiest ways is by using the "+" operator.

Write a program which does the following:

You have two lists
list1 = ["Tomatoes","Potato","Onion"]
list2 = ["Apple","Banana","Watermelon"]
Create a new list - 
x
x and store the value of concatenation of the above lists in 
x
x
Output the new combined list 
x
x to the console

```c
list1 = ["Tomatoes","Potato","Onion"]
list2 = ["Apple","Banana","Watermelon"]
x = list1 + list2
print(x)
 ```
 
 Output
 ['Tomatoes', 'Potato', 'Onion', 'Apple', 'Banana', 'Watermelon']
 
 
 
 
 Removing items from a list
 
 There are multiple ways of deleting elements from a List.

The pop() method removes the item with the specified index number.
The remove() keyword removes the item with the specified name.
The clear() method empties the List.
Task
Write a program for the following:
Create a list = ["Sun", "Moon", "Water", "Sand", "Air"]
Remove the item with the index number 3 and display the list.
Empty and display the list.


```c
c = ["Sun","Moon","Water","Sand","Air"]
c.pop( 3 )
print(c)
c.clear()
print(c)
```

output
['Sun', 'Moon', 'Water', 'Air']


Append and Pop commands

We can use the append() method to add an element at the end of a list.

On the flip side if we want to remove the last element of a list we use the pop() method without providing any index.

Write a program for the following -

Add an item "Jupiter" to the end of the given list.
Remove the last element from the given list using the pop method.
Display both outputs.



```c
planet = ["Venus", "Earth", "Mars"]
planet.append("Jupiter")
print(planet)
planet.pop()
print(planet)
```

Output

['Venus', 'Earth', 'Mars', 'Jupiter']
['Venus', 'Earth', 'Mars']




