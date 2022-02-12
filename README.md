# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
first we need to open the required file from which we need to copy the text

### Step 2: 
 using keyword"with"to open the empty file

### Step 3: 
again using the with keyboard to open the empty file

### Step 4:  
the empty file is opened by using"w" which is used to write only

### Step 5: 
The for function is used to take each line from the main file

### Step 6: 
write() is used to write the lines of main file to the empty file or to he directed file

## PROGRAM:

with open("file1.txt","r") as fp:
    with open("file2.txt","w") as fp1:
        V = fp.read()
        fp1.write(V)
        
### OUTPUT:
![output](.//p1.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.