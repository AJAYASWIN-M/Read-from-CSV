# Read-from-CSV

## AIM:

## ALGORITHM:
### step1
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Print the output.

## PROGRAM:
```
# Developed by:AJAY ASWIN.
# Register Number: 22009045

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![sdfghj](https://user-images.githubusercontent.com/118679692/214784060-da3b49e8-2cc5-43f2-b8fd-7d62a4bfec50.jpeg)

## RESULT:
Thus,the experiment was executed successfully.
