# Read-from-CSV

## AIM:
to write a python program to read contents from a CSV file

## ALGORITHM:

### Step 1:
import panda module as pd

### Step 2:
read the csv file

### Step 3:
print 10 rows

### Step 4:
print the next 5 rows

### Step 5:
print the total no.of rows and columns with argument 1 for column.

## PROGRAM:

import pandas as pd 

df=pd.read_csv("nba.csv")

print(df.head(10))

print(df.tail())

print("rows",df.axes[1])

print("no of rows",len(df.axes[0]))

print("no. of columns",len(df.axes[1]))

## OUTPUT:
![Screenshot 2024-01-01 132335](https://github.com/23004345/Read-from-CSV/assets/138849203/9660457a-3878-4caf-931b-35824003e74a)


## RESULT:
The program is executed successfully
