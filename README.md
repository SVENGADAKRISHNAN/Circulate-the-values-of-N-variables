# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
Program to circulate N values.
Developed by : S VENGADA KRISHNAN
Reference no : 212223110061
def circulate():
    b=a[n:]+a[:n]#a[n:] gives the value after 2 nd place her and adding a[:n] gives the value before the 2nd place.WE ARE USING + TO COMBINE THEM TOGETHER   
    print("After circulating the values are:",b)
a=eval(input())#list or tuple or any
n=int(input())#integer

## Output:

![circulate](https://github.com/SVENGADAKRISHNAN/Circulate-the-values-of-N-variables/assets/147473084/fdd6a9c7-faff-4b41-b9ad-023ddd426c63)



## Result:
The output for circulate the values of n variables is successfull.
