# Read-from-CSV

## AIM:

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
Developed by: JANARTHANAN V K
Register no:212222230051
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(8))
print(f.tail())
print('Number of Rows:',len(f.axes[0]))
print('Number of Column:',len(f.axes[1]))
```
## OUTPUT:
![244468927-1584b1b4-f609-46cb-907b-5a6bd31cd00b](https://github.com/Janarthanan2/Read-from-CSV/assets/119393515/8e6f9797-e512-418b-90ff-b36c0cef8396)

## RESULT:
