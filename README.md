# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.

### Step 2: 
Open file and in the place of filename enter sys.argv[1]. When filename is entered in the command promt, it gets replaced with filename. 
 
### Step 3: 
Read the file and split it. Store the data in a variable.

### Step 4:  
Use built in function len to find len of the stored data.

### Step 5: 
Print the number of words to display it.

### Step 6: 
End Program.

## PROGRAM:
```
#Program to count the number of words in a file using command lines.
#Developed by: Cynthia Mehul J
#Register Number: 23009725

import sys
f=open(sys.argv[1],'r')
a=f.read().split()
word=(len(a))
print("Number of words:",word)
```

### OUTPUT:
![label](/Program.jpg)

![label](/CMD%20Output.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
