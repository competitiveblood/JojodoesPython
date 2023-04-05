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

```c
for i in range(11): 
    if i == 8:
        break
    #Note that print is being executed AFTER the if / break condition.
    #What is the importance of this?
    print(i)
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



## Table of Any number

```c
i = int(input())
for j in range(1,11):
  print(i, 'x', j, '=', i * j)
 ```
 
 Input
 
10

 Output 
 
 10 x 1 = 10
10 x 2 = 20
10 x 3 = 30
10 x 4 = 40
10 x 5 = 50
10 x 6 = 60
10 x 7 = 70
10 x 8 = 80
10 x 9 = 90
10 x 10 = 100


##  While Loop

Similar to the "for" loop, Python also has a "while" loop with which we can execute a set of statements as long as a condition is true.

Print i as long as i is less than 6:

```c
              i = 1
              while i < 6:
                  print(i)
                  i += 1
     Note: remember to increment i, or else the loop will continue forever.
 ```
 
 
 ```c
 a = 0
while a< 9:
 print(a)
 a = a+1
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

## Skipping elements in While loop


all value of c to the console from 1 till 15 but skip printing 11.


```c
#Update the '_' in the code below to solve the problem

c = 0

#Note that print(c) is coming after c = c + 1
#How does this change the condition of the while loop?
while c < 15 :
  c = c + 1
  if c == 11 :
   continue
  print(c)
 ```
 
 Output
 
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
12
13
14
15


##  Sequence of numbers

```c
a = 4
while a < 25:
 a = a+1
 if a == 21:
  continue
 print(a)
print("No more numbers are less than or Equal to 25")
```

Output

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
22
23
24
25
No more numbers are less than or Equal to 25


## Making patterns with Nested Loops

A nested loop is a loop inside a loop. 
The "inner loop" will be executed completely for each single iteration of the "outer loop"

```c
rows = int(input())
for i in range(rows):
    for j in range(i+1):
        print(j+1, end="")
    print("")
  ```
  
  Output
  
1
12
123
1234
12345
123456


 
