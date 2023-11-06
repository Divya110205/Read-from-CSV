# Read-from-CSV

## AIM:

To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1: 

Import pandas module as pd.

### Step 2: 

Using pd.read_csv() method read the CSV file.

### Step 3: 

Using df.head() print the first 10 rows of the CSV file.

### Step 4: 

Using df.tail() print the last 5 of the CSV file.

### Step 5: 

Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
# Exp6- Read from CSV
# Program Developed By: DIVYA.A
# Register Number: 212222230034
import pandas as pd
f=pd.read_csv('/content/Placement_Data.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:

![Exp 6(1)](https://github.com/Divya110205/Read-from-CSV/assets/119404855/51af3c01-3ea2-452f-8cfc-265cae3c7805)
![Exp 6(2)](https://github.com/Divya110205/Read-from-CSV/assets/119404855/2701a94e-4780-420f-91be-f14dcca110d7)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
