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
### Program to find the maximum marks without using the list method sort.
### Developed by : DURGADEVI P
### Register no : 212223100006
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
### Program to find the maximum marks without using the list method max().
### Developed by : DURGADEVI P
### Register no : 212223100006
```
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```
### Program to find the maximum marks without using builtin functions.
### Developed by : DURGADEVI P
### Register no : 212223100006
```
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max
```
## Output:

![output](/max%201.png)
![output](/max%202.png)
![output](/max%203.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
