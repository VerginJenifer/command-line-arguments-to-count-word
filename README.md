# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
#Developed by: D Vergin Jenifer
#Register no.: 23004210
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:

![image](https://github.com/VerginJenifer/command-line-arguments-to-count-word/assets/136251012/ad1b8ee9-1898-473b-a963-5e1b565e4780)


![image](https://github.com/VerginJenifer/command-line-arguments-to-count-word/assets/136251012/d54b51cf-4f02-4010-8ab5-3f0ebff5bc2e)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
