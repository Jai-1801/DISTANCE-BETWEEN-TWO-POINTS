# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the 'math' library.
### Step 2: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 3:
 Take user input for the coordinates of both points (x1, y1) and (x2, y2).
### Step 4: 
Call the distance function with the provided coordinates.
### Step 5: 
Display the distance between the two points as the output.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by:Jai Surya
#RegisterNumber:23002572
import math as m
first=[10,6]
lst=[4,2]
distance=m.sqrt((first[0]-lst[0])**2+(first[1]-lst[1])**2)
print("{:.2f}".format(distance))
```


### OUTPUT:
![OUTPUT](/image.png)

### RESULT:
Thus the Python program calculates and displays the distance between two points in a 2D plane based on the user-provided coordinates.