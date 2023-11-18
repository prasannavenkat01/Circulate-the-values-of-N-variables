# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program.
### Step 2: 
Get the input from the user using eval(input()).
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5: 
Using concatination operation display the entire rotated list.
### Step 6: 
Stop the program.
## Program:
```
#Program to circulate N values.
#Developed by: PRASANNA V
#RegisterNumber: 23006873

def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result) 
    
 
```
## Output:
![Screenshot 2023-11-18 085553](https://github.com/prasannavenkat01/Circulate-the-values-of-N-variables/assets/150702500/96e764fc-8b76-42b0-a78a-6bfdbd9a6a04)


## Result:
Thus the python program for circulate the values of n variables is executed successfully.
