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
#Program to circulate N values.
#Developed by: Sundaramurthy M
#RegisterNumber:23010238
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n: ]+a[ :n]
    print('After circulating the values are:',a)
```
## Output:
<img width="1440" alt="Screenshot 2023-11-18 at 9 27 58 AM" src="https://github.com/Murthy46/Circulate-the-values-of-N-variables/assets/145112768/c6eb9e6c-91fe-4a59-8225-0198c9ff8b81">

## Result:

Thus the python program to circulate the n variable using function concept is successfully executed.
