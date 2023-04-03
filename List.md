
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
