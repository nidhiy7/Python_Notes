# My Python Notes
## Table Of Contents <a name="top"></a>

1. [Introduction](#1)  
2. [Basic Python 3 Syntax Reference](#2)    
   2.1   [Comments](#2.1)    
   2.2   [Importing Libraries](#2.2)    
   2.3   [Print](#2.3)    
   2.4   [Variables](#2.4)    
   2.5   [Arithmetic](#2.5)    
   2.6   [More Arithmetic](#2.6)    
   2.7   [Lists](#2.7)    
   2.8   [List Methods](#2.8)    
   2.9   [Tuples](#2.9)    
   2.10 [Dictionaries](#2.10)    
   2.11 [Dictionary Methods](#2.11)    
   2.12 [Sets](#2.12)    
   2.13 [Set Methods](#2.13)    
   2.14 [Conditionals](#2.14)    
   2.15 [Ternary Operators](#2.15)    
   2.16 [User Input](#2.16)    
   2.17 [For Loops](#2.17)    
   2.18 [Handy For Loop Functions and Keywords](#2.18)    
   2.19 [While Loops](#2.19)    
   2.20 [Strings](#2.20)    
   2.21 [String Functions](#2.21)    
   2.22 [Exception Handling and Debugging](#2.22)    
   2.23 [Iterations, Iterables, Iterators, and More!](#2.23)    
3. [Reference Links](#3)

Python is easy to learn as a first language, and can be said to be 'elegant' in some views. It is very good for prototyping because it does a lot of work for you (like trash and memory management.) You also don't need to care so much about variable types because it automatically assigns them for you!

## 2. Basic Python 3 Syntax Reference <a name="2"></a>

### 2.1 Comments <a name="2.1"></a>

[go to top](#top)

Comments are meant to increase readability for programmers, and will be ignored by computers!

```python
# this is a comment

''' 
multi
line comment!
'''
```
### 2.2 Importing Libraries <a name="2.2"></a>

[go to top](#top)

```python
import <MODULE_NAME>

# If you make your own, say... my_module.py
# This works too!

import my_module
```

Sometimes you want to extend the functionalities of your Python installation by importing modules (libraries of functions other people have written.)

Common useful modules from the standard library that comes installed with Python include:

```python
import math
import decimal
import datetime
import time
import re # Regular Expressions, check my tutorial
import sympy
import sys # For OS commands!

# When you import using import, you invoke module methods like so
math.pi
math.e

# When you import using from
from math import e

# The imported method fills the namespace and you call it without invoking the module name
print(e)
# Output: 2.718281828459045

# Handy ones are stuff like
from math import pi, e
from sympy import diff # diff(expression, variable, order of derivative)
```
```python
# If you're NOT SURE WHAT'S IN THE LIBRARY
# Do

dir(<library>)

# It'll print out all the commands in the library for you to use!
```

