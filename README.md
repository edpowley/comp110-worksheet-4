# COMP110 Worksheet 4

<!--

## Truth Table Template (1 node)

**A**

| A   | Output |
| --- | ------ |
| 0   | 0      |
| 1   | 1      |

## Truth Table Template (2 nodes)

**A xor B**

| A   | B   | Output |
| --- | --- | ------ |
| 0   | 0   | 0      |
| 1   | 0   | 1      |
| 0   | 1   | 1      |
| 1   | 1   | 0      |

## Truth Table Template (3 nodes)

**??**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | 0      |
| 1   | 0   | 0   | 0      |
| 0   | 1   | 0   | 0      |
| 0   | 0   | 1   | 0      |
| 1   | 1   | 0   | 0      |
| 1   | 0   | 1   | 0      |
| 0   | 1   | 1   | 0      |
| 1   | 1   | 1   | 1      |

## Truth Table Template (4 nodes)

**??**

| A   | B   | C   | D   | Output |
| --- | --- | --- | --- | ------ |
| 0   | 0   | 0   | 0   |        |
| 1   | 0   | 0   | 0   |        |
| 0   | 1   | 0   | 0   |        |
| 0   | 0   | 1   | 0   |        |
| 1   | 1   | 0   | 0   |        |
| 1   | 0   | 1   | 0   |        |
| 1   | 0   | 0   | 1   |        |
| 0   | 1   | 1   | 0   |        |
| 0   | 1   | 0   | 1   |        |
| 0   | 0   | 1   | 1   |        |
| 1   | 1   | 1   | 0   |        |
| 1   | 1   | 0   | 1   |        |
| 1   | 0   | 1   | 1   |        |
| 0   | 1   | 1   | 1   |        |
| 1   | 1   | 1   | 1   |        |

-->

## Question 1

> Write out the truth tables for the following boolean expressions, for all possible values of boolean variables A, B, C, . . .

### 1A

TODO:
**A and B and not C**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | 0      |
| 1   | 0   | 0   | 0      |
| 0   | 1   | 0   | 0      |
| 0   | 0   | 1   | 0      |
| 1   | 1   | 0   | 1      |
| 1   | 0   | 1   | 0      |
| 0   | 1   | 1   | 0      |
| 1   | 1   | 1   | 0      |

### 1B

TODO:
**A and not (B and not C)**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | 0      |
| 1   | 0   | 0   | 1      |
| 0   | 1   | 0   | 0      |
| 0   | 0   | 1   | 0      |
| 1   | 1   | 0   | 1      |
| 1   | 0   | 1   | 1      |
| 0   | 1   | 1   | 0      |
| 1   | 1   | 1   | 1      |

### 1C

TODO:
**(A or not B) and (A or C)**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | 0      |
| 1   | 0   | 0   | 1      |
| 0   | 1   | 0   | 1      |
| 0   | 0   | 1   | 0      |
| 1   | 1   | 0   | 1      |
| 1   | 0   | 1   | 0      |
| 0   | 1   | 1   | 1      |
| 1   | 1   | 1   | 1      |

### 1D

TODO:
**A and not (B or not C) and (not A and D)**

| A   | B   | C   | D   | Output |
| --- | --- | --- | --- | ------ |
| 0   | 0   | 0   | 0   | 0      |
| 1   | 0   | 0   | 0   | 0      |
| 0   | 1   | 0   | 0   | 0      |
| 0   | 0   | 1   | 0   | 0      |
| 1   | 1   | 0   | 0   | 0      |
| 1   | 0   | 1   | 0   | 0      |
| 1   | 0   | 0   | 1   | 1      |
| 0   | 1   | 1   | 0   | 0      |
| 0   | 1   | 0   | 1   | 0      |
| 0   | 0   | 1   | 1   | 0      |
| 1   | 1   | 1   | 0   | 0      |
| 1   | 1   | 0   | 1   | 0      |
| 1   | 0   | 1   | 1   | 0      |
| 0   | 1   | 1   | 1   | 0      |
| 1   | 1   | 1   | 1   | 1      |

## Question 2

> Draw logic circuits for each of the expressions in Question 1.

### 2A

![Clean Redstone](redstone/Clean2A.jpg)

- [SVG (2A)](./circuits/2A.svg)
- [Redstone (2A)](./redstone/Diagram2A.png)

### 2B

![Clean Redstone (2B)](redstone/Clean2B.jpg)

- [SVG (2B)](./circuits/2B.svg)
- [Redstone (2B)](./redstone/Diagram2B.png)

### 2C

![Clean Redstone](redstone/Clean2C.jpg)

- [SVG (2C)](./circuits/2C.svg)
- [Redstone (2C)](./redstone/Diagram2C.png)

### 2D

![Clean Redstone](redstone/Clean2D.jpg)

- [SVG (2D)](./circuits/2D.svg)
- [Redstone (2D)](./redstone/Diagram2D.png)

## Question 3

> Use truth tables to show that the following identities hold:

### 3A

CHECK:
**NOT (A OR B) = NOT A AND NOT B**

| A   | B   | Output |
| --- | --- | ------ |
| 0   | 0   | 1      |
| 1   | 0   | 0      |
| 0   | 1   | 0      |
| 1   | 1   | 0      |

### 3B

CHECK:
**NOT (A AND B) = NOT A OR NOT B**

| A   | B   | Output |
| --- | --- | ------ |
| 0   | 0   | 1      |
| 1   | 0   | 1      |
| 0   | 1   | 1      |
| 1   | 1   | 0      |

### 3C

TODO:
**(A AND B) OR (A AND C) = A AND (B OR C)**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   |        |
| 1   | 0   | 0   |        |
| 0   | 1   | 0   |        |
| 0   | 0   | 1   |        |
| 1   | 1   | 0   |        |
| 1   | 0   | 1   |        |
| 0   | 1   | 1   |        |
| 1   | 1   | 1   |        |

### 3D

TODO:
**(A OR B) AND (A OR C) = A OR (B AND C)**

| A   | B   | C   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   |        |
| 1   | 0   | 0   |        |
| 0   | 1   | 0   |        |
| 0   | 0   | 1   |        |
| 1   | 1   | 0   |        |
| 1   | 0   | 1   |        |
| 0   | 1   | 1   |        |
| 1   | 1   | 1   |        |

## Question 4

> Explain, using the identities in Question 3 and/or truth tables, why each
of the following pairs of programs is equivalent:

### 4A

TODO:
```py
if not ( file_exists ("a . txt ") and file_exists ( "b. txt " )):
	print ("A required file is missing ")
	
if not file_exists ("a . txt ") or not file_exists (" b. txt " ):
	print ("A required file is missing ")
```

### 4B

TODO:
```py
if ( type ( x) == int and x > 7) or ( type (x) == float and x > 7):
	print (" Hello ")
	
if ( type ( x) == int or type (x ) == float ) and x > 7:
	print (" Hello ")
```

### 4C

TODO:
```py
if x == 0 and y == 0:
	do_something ()
else :
	print (" Do nothing ")
	
if x != 0 or y != 0:
	print (" Do nothing ")
else :
	do_something ()
```

### 4D

TODO:
```py
if x > 10 or (x > 0 and y > 0):
	do_something ()
	
if x > 0 and (x > 10 or y > 0):
	do_something ()
```
