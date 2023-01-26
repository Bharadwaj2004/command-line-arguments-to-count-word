# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name using command arguments
### Step 2: 
Get the file name using command arguments
### Step 3: 
use split()
### Step 4:  
Now read the no.of words in file
### Step 5: 
Print number of words present in given file
### Step 6: 
End of the program
## PROGRAM:
```python
Developed By: B.Venkata Bharadwaj
# Reference number: 22003979
import sys
count = 0
with open("text.txt",'r') as f:
    for line in f:
        word =line.split()
        count+=len(word)
print("Word count in file: ",count)
```
### OUTPUT:
![WhatsApp Image 2023-01-26 at 2 54 50 PM](https://user-images.githubusercontent.com/119560345/214802728-75aacda2-db6e-4ffa-8a3f-a86a26e573f4.jpeg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
