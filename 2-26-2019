%## running a whole file at once
% ## dunder file: tells you where the file is saved
print(__file__)

if __name__ == '__main__': print(__file__)


# Two ways to import: import a module or import a function from a module
# If you import a module, you need to use it as a namespace with dot notation
# Use 'as' to alias a package name, e.g. import pandas as pd
# In normal mode, type gg to go to top, G to go bottom, 9gg or 9G to go to line 9
# ideavimrc: space is to run current line
# 50% takes you to the middle of a file
# ideavimrc: surround, e.g. ys$' to surround the rest of the line with '
# V selects a line, then you can expand the selection by moving around
# with multiple lines selected, press alt+shift+E to run multiple lines of code
import math # import math module


from math import sqrt # import a function

# math.sqrt(4) will protect the sqrt function and just call it from the math module
sqrt = sqrt(4)
sqrt(4)
#the above line does not run becasue sqrt function already assigned
#math.sqrt(4) works! "namespace" math protects the function "sqrt"
math.sqrt(4)

from math import pi # import an attribute
math.pi

import numpy as np # follows convention (np is an alias for numpy)


import pandas as pd # follows convention
pd.concat()

from pandas import * # (* = EVERYTHING! very NOT good idea!!)
#pandas is a library because it has many modules. its alias is "pd"
concat() #dont have to use an alias if you import everything from pandas, butt bad because you overwrite things that exist in python. Dunderfile needed to protect

from pandas import DataFrame # generally not a good idea

math.sqrt # a function
math.pi # an attribute

sqrt(42)
pi

# fun imports

# opens a poem called the Zen of Python
import this
this

# Says "Hello world!" Imports that notorious code instead of you writing it
import __hello__
__hello__

# gives a syntax error "not a chance!"
from __future__ import braces

# takes you to an xkcd comic
import antigravity


# Antigravity comic: https://xkcd.com/353/
# What does whitespace mean in the antigravity comic?
for i in range(10):
    print('a') # included in the loop
    print(i) # included in the loop
print('b') # not included in the loop
print(i) # not included in the loop

# What does it that Python is dynamically typed?
x = 5
x = '5'

# You can include type hints (optional, but helpful)
x: int = 5 # i expect x to be an integer 5
x: str ='5' #expect x to me a string
x

# print is a function in python 3, but a statement in python 2
print("Hello world")

# namespaces are useful
# The example below shows a name conflict with the list function
list = [1, 2, 3] # list variable conflicts with list function
list() # TypeError! 'list' object is not callable
del list # remove the list variable
list() # Should be ok now.


def multiply(x: int, y: int) -> int:
    """ this funtion returns an int"""
    return x * y
    2*3 #gives 6

def multiply(x: str, y: int) -> int:
    """ this funtion returns an int"""
    return x * y
    '2'*3 #gives "222" (string '2' 3 times)
