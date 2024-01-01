# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
## PROGRAM:
```
# Python program for copying elements from one file to another.
# Developed by:Bhuvanesh.S.R
# Register Number:212223240017

a=open("file.txt","r")
b=open("file1.txt","w")
r_a=a.read()
b.write(r_a)
```
### OUTPUT:
![exp 5c python ss](https://github.com/Bhuvanesh-Suresh/copy-file/assets/145742661/5c05679e-a389-4c61-a4e7-4e770924bacc)
![Screenshot 2024-01-01 220847](https://github.com/Bhuvanesh-Suresh/copy-file/assets/145742661/008e409f-0676-4e3a-bcaf-d51f4d1f9022)
![Screenshot 2024-01-01 221236](https://github.com/Bhuvanesh-Suresh/copy-file/assets/145742661/a00bb663-6175-4570-b640-9b8c9e960fb0)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
