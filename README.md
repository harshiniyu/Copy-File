# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
 Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
#Developed by: HARSHINI Y
#Register Number: 212223240050

with open("text1.txt", 'r') as fp:
    msg=fp.read()
with open("copy.txt", 'w') as fp1:
    fp1.write(msg)

```
### OUTPUT:

![image](https://github.com/harshiniyu/Copy-File/assets/144979786/690a7225-3e1e-4818-839f-ce8dab0b3778)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
