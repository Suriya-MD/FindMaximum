## Date:
# Exp-6: Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
Developed by: SURIYA M

RegisterNumber : 212223110055

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(array):
    array.sort()
    return array[-1]

```
## Output:
![image](https://github.com/user-attachments/assets/c03b67bc-06e4-41b4-ac6b-e4bfe31c144f)


ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(array):
    return max(array)

```
## Output:
![image](https://github.com/user-attachments/assets/34c264fc-477a-4b59-a87f-3ddf2559fa08)


iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1

```

## Output:
![image](https://github.com/user-attachments/assets/bef1bb4e-fec4-454d-890e-9fcebd2ed990)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
