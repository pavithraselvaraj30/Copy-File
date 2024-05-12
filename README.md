# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:   
 Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().
### Step 3: 
The number of rows returned is defined in pandas option settings.
### Step 4:  
check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame.
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: PAVITHRA S
#Register Number: 212223230147

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

### OUTPUT:

![Screenshot 2024-05-12 112643](https://github.com/pavithraselvaraj30/Copy-File/assets/149366880/b5777665-f330-4791-876a-983008fd0966)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
