# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
Get the n values from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
print the output 
### Step 6: 
end the program
## Program:

```
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print('After circulating the values are:',result)
```
## Output:

![output](https://github.com/BHARATHNATRAJAN/Circulate-the-values-of-N-variables/assets/147473529/4b86399a-c3f3-4ed6-9448-1c3ba496f463)

## Result:

the given program is executed successfully
