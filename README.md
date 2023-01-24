# Read-from-CSV

## AIM:
To write a python code to read data from CSV file.
## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.
## PROGRAM:
```
#Devloped By:KAVINESH M
#Ref no:22008476
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:
![CSV](https://user-images.githubusercontent.com/118466561/214219578-4f0c3ed1-41a7-4fae-bb6d-35e305c541ac.png)

## RESULT:
A python program to read data from CSV files has been created successfully.
