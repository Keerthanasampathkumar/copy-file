# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Start the program

### Step 2:
Open file1.txt in read mode

### Step 3:
aasign paar to fp.read() of file1.txt

### Step 4:
again open a new file file2.txt in write mode

### Step 5:
use write function to copy the file contents

### Step 6:
End the program

## PROGRAM:
```
Developed by : KEERTHANA S
RegisterNumber:22009006
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:

![git 1](https://user-images.githubusercontent.com/119477890/215125650-9fa8e4b5-409d-4eae-9c71-7396f295fbd4.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
