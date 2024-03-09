# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
define a function as circulate
### Step 2: 
get the valuse from the user for the list using eval()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the output usring print statement
## Program:
```
def circulate():
    num=eval(input())
    n=int(input())
    print("After circulating the values are:",num[n:]+num[:n])
```
## Output:
![alt text](<Screenshot from 2024-03-09 09-14-51.png>)

## Result:
thus the program is successfully executed
