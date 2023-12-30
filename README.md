# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import the pandas library as "pd".

### Step 2:
Read the CSV file "cars.csv" using read_csv() method and assign it to the variable "df".

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.

### Step 5:
Print the output and end the program.
## PROGRAM:
```python
#Program to read contents from a csv file
#Developed by :Aravindkumar ss
#Register nuumber:23004721
import pandas as pd
df=pd.read_csv('/content/cars (1) (4).csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:
![Screenshot 2023-12-30 230956](https://github.com/aravindkumar23004721/Read-from-CSV/assets/148962674/1f63cc31-8677-4db8-a898-d6d8dd0844bf)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
