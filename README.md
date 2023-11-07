# Read-from-CSV

## AIM:
To develop a python program to read a file rom csv.
## ALGORITHM:
### Step 1: Import the pandas function as pd.
### Step 2: Read the file and store it in the variable f.
### Step 3: Print the head and tail.
### Step 4: Print the number of rows using the length function(len).
### Step 5: Print the number of coloumns using the same length function(len).
## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(0))
print(f.tail())
print('Row:',len(f.axes[0]))
print('col:',len(f.axes[1]))
```
## OUTPUT:

![image](https://github.com/sanjay5656/Read-from-CSV/assets/115128955/bf50b200-470a-4c96-a8b0-32b5705df50f)

## RESULT:
Thus the program is successfully executed.
