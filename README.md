# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1: 
Import the sys module.

# Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

# Step 3:
Read the file using read() method.

# Step 4: 
Use split() method to split the file content into words.

# Step 5: 
Use len() to find the total words.

# Step 6:
Run the program to determine the number of words in the file created.

# PROGRAM:
```
#program is developed by:Rajesh A
#REF.NO: 22008551
```
```
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: SATHISH.R")
print("word count in file = ",count)
```
# OUTPUT:
![ae04b21a-33b6-42f3-bc82-e586cce54e30](https://user-images.githubusercontent.com/118924713/214757764-a52c9b7f-e90a-4012-8d65-ecdc39523dd0.jpg)

![6b2870db-bc33-4ce0-adf7-e432e127655e](https://user-images.githubusercontent.com/118924713/214757775-22414434-62ec-44e1-85ad-68a25a1e3a3b.jpg)

# RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
