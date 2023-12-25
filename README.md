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
```Python
Program to mark the maximum of marks using the list method sort
Developed by: saranya s
RegisterNumber: 23013399
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: saranya s
RegisterNumber:23013399 
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:saranya s
RegisterNumber:23013399
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/srisrisaranya/FindMaximum/assets/148516638/889a65f5-d041-4edd-a33d-2ae4fbf8a77b)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/srisrisaranya/FindMaximum/assets/148516638/77110af6-f2cd-4c4c-befc-dffe57f92960)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/srisrisaranya/FindMaximum/assets/148516638/0ef09cc0-1e65-4ef7-ae53-884cc8564946)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
