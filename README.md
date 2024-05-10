# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.
### Step 2: 
Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
## PROGRAM:
```
fname = input('enter the file name')
num_words = 0
with open(fname, 'r') as f:
  for line in f:
   words = line.split()
   num_words+=len(words)
print('Number of words:',num_words)

```

### OUTPUT:

![WhatsApp Image 2024-05-10 at 7 44 34 PM](https://github.com/Hemaatchu/Command--line-arguments-to-count-word/assets/147328300/3e2d371a-2f0a-48c8-b006-b6ed944931bb)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
