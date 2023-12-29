# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module.
### Step 2: 
Pass the file name as the first argument after the name of the script open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
use split() method to split the file content into words
### Step 5: 
use len() to find the total words
### Step 6: 
run the program to determine the number of words in the file created.

## PROGRAM:
```
Developed by:Harrish Venkat V
Register No:23013973

import sys
fp = open(sys.argv[1])
data = fp.read()
words=data.split()
print("Total words:",len(words))
```
### OUTPUT:

![293391965-d2ecc033-5119-4bc2-abf2-a7e7613c3091](https://github.com/HarrishVenkat/command-line-arguments-to-count-word/assets/144979588/759c392b-95dc-42c8-a04f-f18c9e18e78c)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
