# Read-from-CSV

## AIM:
    Write a program to read a csv file.
## ALGORITHM:

## Step 1:
    Import pandas module as pd
## Step 2:
    Read a csv file name cars.csv
## Step 3:
    print the first five rows and last five rows
## Step 4:
    print the length of the rows and columns
## Step 5:
    End the program
## PROGRAM:
```
"""write a program to read a csv file
Developed by :SUNIL KUMAR T
Reference no:23001650
"""
import pandas as pd
df=pd.read_csv("/content/drive/MyDrive/cars .csv")
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))

```

## OUTPUT:
![output](/Screenshot%202023-07-31%20093158.png)
![output](/Screenshot%202023-07-31%20093705.png)

## RESULT:
  Thus the program is written to read a csv file.

