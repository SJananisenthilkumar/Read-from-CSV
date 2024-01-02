# Read-from-CSV
## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output
## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : JANANI S
#Register Number:23013409

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/SJananisenthilkumar/Read-from-CSV/assets/144871139/5b3a6033-f877-40d4-bf6a-6183ecce19f6)

## RESULT:
Thus the program is written to copy the contents from one file to another file
