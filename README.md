# Read-from-CSV

## AIM:

## ALGORITHM:
Step 1:
Import pandas module as pd.

Step 2:
Using pd.read_csv() method read the CSV file.

Step 3:
Using df.head() print the first 10 rows of the CSV file.

Step 4:
Using df.tail() print the last 5 of the CSV file.

Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: PREETHA.S
#RegisterNumber: 212222230110
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:

![image](https://github.com/Preetha-Senthamilan/Read-from-CSV/assets/119390282/8d9a6ea3-ad5d-459e-824f-6e03dba64cb3)


## RESULT:

Hence the python programe to read the contents from a csv file is executed successfully.
