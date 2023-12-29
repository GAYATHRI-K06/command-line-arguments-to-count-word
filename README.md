# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
 using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
``````

Develpoed By:GAYATHRI.K
RegisterNumber:23013439

import sys
fp=open(sys.argv[1])
data=fp.read()
words=data.split()
print("no of words",len(words))
``````


### OUTPUT:
![Screenshot 2023-12-29 205646](https://github.com/GAYATHRI-K06/command-line-arguments-to-count-word/assets/145742742/c2447a91-6467-4409-8da0-72f2dcd578d2)
![Screenshot 2023-12-29 205709](https://github.com/GAYATHRI-K06/command-line-arguments-to-count-word/assets/145742742/7740f473-6ebf-461d-afe6-957a8308578a)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
