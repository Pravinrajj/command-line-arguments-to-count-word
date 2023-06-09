# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
initially make count = 0

### Step 3:
open the content file using command line arguments.

### Step 4:
by using for loop name the function as "line"

### Step 5:
split the line using .split

### Step 6:
split the line using .split

## PROGRAM:
```
import sys
fp=open(sys.argv[1],"r")
d={}
for i in fp:
    for w in i.split():
        if w not in d.keys(): 
            d[w]=1
        else:
            d[w]+=1
print(d)
```

### OUTPUT:
![Uploading Screenshot from 2023-01-28 15-38-40.png…]()


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
