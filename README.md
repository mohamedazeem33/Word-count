# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open visual studio code or jupyter lab

### Step 2: 
create file with .py extension
 
### Step 3: 
also create .txt file and input sentences

### Step 4:  
write the code

### Step 5: 
run the program

### Step 6: 
print the values and end the program

## PROGRAM:
```python
#program for getting the word count from a text
#developed by:MOHAMED AZEEM N
#reference no:22007405
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```

### OUTPUT:

![python exp 5](https://user-images.githubusercontent.com/121040764/214794056-3936e46e-ae73-4737-a66b-0d6d984f9fa0.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
