# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
## Step 1:
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns.

## Step 5:
Display the result.


## PROGRAM:
'''
To write a python program for reading content from a CSV file.
Developed by: Goutham.K
Register No: 212223110019
'''

import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

## Program file: 
![image](https://github.com/Goutham2306/Read-from-CSV/assets/138971154/37ceeee9-0451-4d13-a113-2c31fc8135a7)

## Output:
![image](https://github.com/Goutham2306/Read-from-CSV/assets/138971154/69c11031-df70-4014-b079-231ec172e942)




## RESULT:
Thus python program for reading content from CSV file is successful.
