Dictionaries are used to store data values in key:value pairs. A dictionary is a collection that is ordered, changeable and does not allow duplicates.



In lists, the index numbers point to the values. But there the index numbers were restricted to be 0, 1, 2, ...



In dictionaries, your keys can be anything you want. Keys are a generalisation of index numbers.





You can access the items of a dictionary by using the get() keyword






```c
x = {"Ram":24,"Rahul":12,"Karan":18}
y = x.get("Rahul")
f = x.get("Karan")
print(y)
print(f)
```

Output
12
18
