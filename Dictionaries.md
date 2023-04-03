# Dictionaries 

Dictionaries are used to store data values in key:value pairs.


A dictionary is a collection that is ordered, changeable and does not allow duplicates.



In lists, the index numbers point to the values. But there the index numbers were restricted to be 0, 1, 2, ...



In dictionaries, your keys can be anything you want. Keys are a generalisation of index numbers.





You can access the items of a dictionary by using the **get()** keyword






```c
x = {"Ram":24,"Rahul":12,"Karan":18}
y = x.get("Rahul")
f = x.get("Karan")
print(y)
print(f)
```

Output
```
12

18
```


## Changing Elements of a Dictionary


There are multiple ways of printing different elements of a dictionary

The **values()** method will return a list of all the values in the dictionary.
The **items()** method will return each item in a dictionary, as (key, value) tuples in a list.



```c
dict = {"Apple":"Red","Banana":"Yellow","Grape":"White"}
k = dict.values()
print(k)
dict["Grape"] = "Green"
print(dict)
```

**Output**

```
dict_values (['Red', 'Yellow', 'White'] )
{'Apple': 'Red', 'Banana': 'Yellow', 'Grape': 'Green'}
```



## Adding pairs to a dictionary

Adding an item to the dictionary can be done by using a new index key and assigning a value to it. 


```c
d = {"Josh":"Guitar","Gary":"Drums","Hik":"Piano"}
d["kurt"] = "flute"
print(d)
```

**Output**

```
{'Josh': 'Guitar', 'Gary': 'Drums', 'Hik': 'Piano', 'kurt': 'flute'}
```



## Removing elements from a dictionary

Similar to Lists there are multiple ways of deleting elements from a dictionary.

The **pop()** method removes the item with the specified key name:
The **del** keyword removes the item with the specified key name and can also delete the whole dictionary
The **clear()** method empties the dictionary:


```c
c = {"Ferrari":1967,"Honda":2001,"Ford":2016}
c.pop("Ford")
print(c)
c.clear()
print(c)
```


**Output**

```
{'Ferrari': 1967, 'Honda': 2001}
{}
```


