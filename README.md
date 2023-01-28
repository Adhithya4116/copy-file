# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Open the first file in read mode

### Step 2: 
 Open the second file in append mode
 
### Step 3: 
Open the second file in append mode

### Step 4:  
close the first file

### Step 5: 
close the second file

## PROGRAM:

python program for copying the contents from one file to another file.
Developed by: adhithya perumal.d
RegisterNumber: 22008747
f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
### OUTPUT:
![5c](https://user-images.githubusercontent.com/118707079/215267726-8714598b-32dc-4d5b-8618-ae8d6ff81a1e.png)
![5](https://user-images.githubusercontent.com/118707079/215267737-24952d2d-45a3-4e91-93a7-60f03a796b11.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
