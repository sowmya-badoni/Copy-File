# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
Print the number of contents to be displayed using df.head() 
### Step 3: 
The number of rows returned is defined in Pandas option settings
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: SOWMYA BADONI
#Register Number: 212223230211

with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)


```
### OUTPUT:
![copy1](https://github.com/sowmya-badoni/Copy-File/assets/152136324/43428ed0-7922-472c-bf04-3a0bcd077aa4)

![copy2](https://github.com/sowmya-badoni/Copy-File/assets/152136324/a5e85f02-9e15-43c9-a4b5-29db2c555bca)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
