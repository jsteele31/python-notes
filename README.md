python-notes
============

Python Notes

""" WHITE SPACE WHITE SPACE WHITE SPACE """
sum
sqrt
min
max
abs



def name(arg):
def name(*arg): #splatter arg

if:
elif:
else:

!=, ==, >, <, >=, <=  # no === in python

and
or # works on True True
not


len()
str()
.upper
.lower
type()

int, float, bool, string

import math
from math import *

list[:4]
list[3:4]
list[3:]

list.insert(index, "object")
list.index("object") # returns index or error
list.append("object")
list.sort()
list.pop(index) # will remove the item at index from the list and return it to you
# or del(list[index]) <-- same but no return
my_list.remove(value)

for varible in listName:
for i in range(0, 3):

# RANGE #
range(1) # => [0]
range(2) # => [0,1]
range(1,3) # => [1,2]
range(2,8,3) # => [2,5] # 3 arguments, the range's first argument is the number the list starts at, the second number is where the list ends, and the third argument is how much you should increment 
range(2,9,3) # => [2,5,8]


Dictionary ex:
residents = {'Puffin' : 104, 'Sloth' : 105, 'Burmese Python' : 106}
# print residents['Puffin'] returns 104
del dict_name[key_name]

########################### {  dictionary }   [ list ]
Small Ex:

inventory = {'gold' : 500,
'pouch' : ['flint', 'twine', 'gemstone'], # Assigned a new list to 'pouch' key
'backpack' : ['xylophone','dagger', 'bedroll','bread loaf']}

# Adding a key 'burlap bag' and assigning a list to it
inventory['burlap bag'] = ['apple', 'small ruby', 'three-toed sloth']

# Sorting the list found under the key 'pouch'
inventory['pouch'].sort() 
# Here the dictionary access expression takes the place of a list name 
inventory['pocket'] = ["seashell", "strange berry", "lint"]

inventory["backpack"].sort()

# Your code here!
inventory["backpack"].remove("dagger")
inventory["gold"] = inventory["gold"] + 50



#########################################################

while (condition):
  tab space
  
while (condition): #yes this is a while else!
else: # it will execute if the loop is never entered or if the loop exits normally

raw_input("question")

from random import randrange
randrange(0, 10)


