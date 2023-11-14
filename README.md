# EX 6: Read-from-CSV
## DATE: 31.10.23
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
#Program to read contents from a CSV file.
#Developed by: DIVYA.A
#RegisterNumber: 212222230034
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Divya110205/Read-from-CSV/assets/119404855/08221689-28f6-418b-bde8-c0fd8b8c5fe0)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
