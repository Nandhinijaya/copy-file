# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Create a text1.txt with some content in it
### Step 2:

Open the text1.txt file in read mode
### Step 3:

Create a copy.txt file using write mode
### Step 4:

Copy the content of text1.txt file to copy.txt using write function
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:E.NANDHINI
RegisterNumber: 212222100030

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![1](https://github.com/Nandhinijaya/copy-file/assets/121998147/f6e3603a-91e7-4d79-9ca4-106b896117fc)

![2](https://github.com/Nandhinijaya/copy-file/assets/121998147/43b75bdd-6d8d-432c-9a2b-1d061baaa117)

![3](https://github.com/Nandhinijaya/copy-file/assets/121998147/4936af56-156f-47e6-a4cf-f343d72c875d)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
