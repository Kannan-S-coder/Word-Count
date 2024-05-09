# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program

## PROGRAM:
```
 program to find the number of words in a text file
 Developed by : Kannan S
Register number : 212223230098
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![WhatsApp Image 2024-05-09 at 05 44 08_9f60a394](https://github.com/Kannan-S-coder/Word-Count/assets/147120710/775b9ba0-c643-4302-ab37-1fa3b64f01c0)
![image](https://github.com/Kannan-S-coder/Word-Count/assets/147120710/b79319f2-55b0-470a-a840-0271a960488a)


## RESULT:
Thus the program is written to find the word count from a text.
