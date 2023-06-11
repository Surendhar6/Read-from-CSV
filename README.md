# Read-from-CSV

## AIM:
To write a python to read data from CSV files.

## ALGORITHM:
### Step 1:
Start python and import pandas.

### Step 2:
The number of rows returned is defined in pandas option settings.

### Step 3:
Read the contents of the CSV file using the df.read function.

### Step 4:
Increase the maximum number of rows to display the entire dataframe.

## PROGRAM:
```
### NAME:SURENDHAR A
### REGISTER NUMBER:212222110049
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("colums",df.axes[1])
print("no. of rows",len(df.axes[0]))
print("no. of colums",len(df.axes[1]))
```

## OUTPUT:
![Screenshot from 2023-06-11 19-30-39](https://github.com/Surendhar6/Read-from-CSV/assets/118352907/8246c7d7-9aec-4048-b5eb-4f5b0fadc4af)

## RESULT:
Thus the program is written to read the csv file.
