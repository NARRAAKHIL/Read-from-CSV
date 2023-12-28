# Read-from-CSV

## AIM:
to write a python program for reading content from a CSV file.

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
Display the result.

## PROGRAM:
```
'''
# Developed by: Narra akhil
# Register Number: 23003406
'''
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/NARRAAKHIL/Read-from-CSV/assets/144979843/cdd935b1-d59e-4949-984f-f00143a34f82)


## RESULT:
thus python program for reading content from CSV file is succwssful.
