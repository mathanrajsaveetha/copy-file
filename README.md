# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create two txt file.A file which has content [lines.txt] to be copied to the empty [text.txt]file.
### Step 2: 
 Using write() function to copy the content from line.txt to empty file,text.txt.
### Step 3: 
Save and run the python program in terminal.
### Step 4:  
The text from the lines.txt file is copied to the empty file text.txt.
### Step 5: 
Then the text is shown in empty file text.txt.
### Step 6: 
Result is obtained.
## PROGRAM:
DEVELOPED BY:MATHAN RAJ E
REFERENCE NO:22008971

with open('lines.txt','r') as file1:
    with open('text.txt','w') as file2:
        for line in file1:
            file2.write(line)

### OUTPUT:
![image](https://user-images.githubusercontent.com/119560501/214980603-4b3b1ddc-d619-4e1b-99f7-11416cd47ba3.png)
![image](https://user-images.githubusercontent.com/119560501/214980715-377ae94f-9eb8-4d26-9f3c-b6d6b59b7391.png)
![file](https://user-images.githubusercontent.com/119560501/214980778-11e11f83-4ecd-4fb7-94a9-944d2a01c3a0.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
