# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The four function is used to take each line from the main file.
## PROGRAM:
```
with open ("text.txt") as fp:
  with open("file.txt","w") as fp1:
    line= fp.read()
    fp1.write(line)
```

### OUTPUT:
![image](https://github.com/PreethiS647/Copy-File/assets/147313372/e84ab2ab-3c40-45ae-a4fc-73aab8e48e9e)

![image](https://github.com/PreethiS647/Copy-File/assets/147313372/6967e472-42c9-40b8-9ba7-d660af02e3aa)

![image](https://github.com/PreethiS647/Copy-File/assets/147313372/5a43d751-e1db-44fb-8178-bfe5cadd4354)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
