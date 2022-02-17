# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import sys.

Step 2:
Assign a variable count =0.

Step 3:
Open a file in read mode.

Step 4:
Iterate a variable(lines) through the file.

Step 5:
Assign a variable words = lines.split().

Step 6:
Now iterate through the variable and increase the count: and print the count value.

## PROGRAM:
```
#Developed By:- G.jayanth
#Reference number:-21005806
import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)  
```

### OUTPUT:-
<img width="590" alt="ga1" src="https://user-images.githubusercontent.com/94836154/154493490-22085270-7147-46de-9d0e-d9c6553bb6ea.png">
<img width="580" alt="ga2" src="https://user-images.githubusercontent.com/94836154/154493540-56b66082-8b07-42ad-a360-b2a0e71cf8f4.png">




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
