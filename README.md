# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2: 
Create a file pointer and open the file.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
### Step 7:
Close the file pointer and end the program.
## PROGRAM:
~~~
Developed by: SORNA KUMAR S
Register no: 212223230210
num=0
with open("count.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
~~~
### OUTPUT:
![image](https://github.com/Sornakumar16/Word-Count/assets/138849327/4b374f79-8861-48af-8a8c-37ba36e48b65)



## RESULT:
Thus the program is written to find the word count from a text.
