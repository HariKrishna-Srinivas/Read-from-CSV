# Read-from-CSV

AIM:
To write a python program for reading content from a CSV file.

ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns

Step 5:
Print the output.
## PROGRAM:
~~~
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print(df.loc[[78,79,80,81],:])
print(len(df.axes[0]))
print(len(df.axes[1]))

## OUTPUT:
~~~
<img width="569" alt="hari1" src="https://user-images.githubusercontent.com/94882905/154801279-16340c5d-8ede-4ffe-a365-957ffce2a9b5.png">

## RESULT:
Thus a python program is written to read the contents of a CSV file.
