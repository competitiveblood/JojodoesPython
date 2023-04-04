# Loops in Python

## For loop

 "for" loop we can execute a set of statements, once for each item in a list, tuple, string etc.

```c
fruit = ["Apple","Grape","Melon","Kiwi","Banana"]
for x in fruit:
  print(x) 
```

Output
Apple
Grape
Melon
Kiwi
Banana

## Skipping items in a looped list

With the "continue" statement we achieve the following

We can stop the current iteration of the loop
We continue with the next element. That is, we will not go any further in this particular iteration, and instead skip to the next iteration.


```c
Mnts = ["Jan", "Feb", "March","Apr","May"]
for x in Mnts:
  if x == "Apr":
     continue
  print(x)
```

Output

Jan
Feb
March
May


## Using for loop in a string

```c
a = "Antarctica"
for x in a:
 print(x)
```

Output


A
n
t
a
r
c
t
i
c
a
S


## Use of Range in for loops

The range() function does the following

Returns a sequence of numbers, starting from 0, and increments by 1 (by default)
It ends at one less than the specified number.


```c
for x in range( 25 ):
  print(x)
print("LOOP ENDED")
```

Output

0
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
 
## Using Custom Range

The range() function can also return a custom sequence of numbers by defining the starting and ending values separated by a comma.

For eg in this range - range(3,15) the loop will start with 3 and end with 14.

```c
or x in range( 4 , 32 ):
  print(x)
```

Output

4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31


## Custom increments in range command

n the previous problem, we learned how to use the range command with the default +1 increments. 
However, it is also possible to specify the increment value by adding a third parameter.

For eg - range(2, 30, 3)
With the third parameter, the loop will add increment by 
3
3 instead of the default


```c
i = 20
for i in range(20,45, 2):
  print( i )
```

Output

20
22
24
26
28
30
32
34
36
38
40
42
44

## Exiting the Loop

We can use the "break" statement to stop the loop before it has looped through all the items.

Note:

"break" functions differently from "continue" that we learnt earlier
"break" exits the loop completely and goes to the next section of the program
"continue" exits the current iteration and skips the code remaining in the current loop iteration.
However, the "for" or "while" loop continues with the next iteration.




