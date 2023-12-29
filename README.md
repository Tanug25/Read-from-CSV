# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
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
Display the result.

## PROGRAM:
Developed by:Tanushree.A
Register No:23004953

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:,len(df.axes[1]))
## OUTPUT:
![jupyter 6 op](https://github.com/Tanug25/Read-from-CSV/assets/138849166/4c3e1d99-0486-4ac2-ad9d-17d36dba234b)


## RESULT:
Thus python program for reading content from a CSV file is successful.
