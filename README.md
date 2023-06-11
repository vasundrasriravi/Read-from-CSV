# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1: Import pandas module as pd.

### Step 2: Using pd.read_csv() method read the CSV file.

### Step 3: Using df.head() print the first 10 rows of the CSV file.

### Step 4: Using df.tail() print the last 5 of the CSV file.

### Step 5: Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: VASUNDRA SRI R
#RegisterNumber: 212222230168

import pandas as pd
f=pd.read_csv('/content/nba(1).csv')
print(f.head(10))
print(f.tail())
print('Number of Row:',len(f.axes[0]))
print('Number of column:',len(f.axes[1]))
```
## OUTPUT:

![Screenshot 2023-06-11 110005](https://github.com/vasundrasriravi/Read-from-CSV/assets/119393983/40f5089c-3d50-42f2-b479-6c654e9dddad)

## RESULT:
Hence the program is executed successfully!
