# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2: 
Read the text using read() function.
 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character

### Step 4:  
The length of the split list should equal the numbers of words in the test file.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 
End the program



## PROGRAM:
```
Developed by:VEDHASHREE.G
Register no: 212223240171
import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```

### OUTPUT:
![image](https://github.com/Vedha0406/Command--line-arguments-to-count-word/assets/150884870/a3062121-7deb-4d2e-8e8a-af4a39311c79)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
