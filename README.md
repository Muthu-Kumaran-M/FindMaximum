# Find the maximum of a list of numbers
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

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Muthu Kumaran M
RegisterNumber: 23006606
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Muthu Kumaran M  
RegisterNumber:23006606
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Muthu Kumaran M
RegisterNumber: 23006606
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Exp 3-a,1](https://github.com/Muthu-Kumaran-M/FindMaximum/assets/144979439/2202bd0d-a25f-492f-a678-d6edff089b18)
![Exp 3-a,2](https://github.com/Muthu-Kumaran-M/FindMaximum/assets/144979439/4fadd1e5-f484-4c83-9ba3-f6feb9de872a)
![Exp 3-a,3](https://github.com/Muthu-Kumaran-M/FindMaximum/assets/144979439/1c2b007a-5da1-40b1-8031-193d97a2c694)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
