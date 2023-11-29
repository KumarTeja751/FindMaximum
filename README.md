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
#Program to mark the maximum of marks using the list method sort
#Developed by: NARAMALA KUMARTEJA
#RegisterNumber: 23003525
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by: NARAMALA KUMARTEJA
#RegisterNumber: 23003525
def max_marks(marks):
    large = max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: NARAMALA KUMARTEJA
#RegisterNumber: 23003525

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/KumarTeja751/FindMaximum/assets/144947756/09e27446-f1fd-46cd-8f13-bd0f416ddbcf)
![image](https://github.com/KumarTeja751/FindMaximum/assets/144947756/8d83c8ab-cb81-4643-8802-a5a8a9475afc)
![image](https://github.com/KumarTeja751/FindMaximum/assets/144947756/642b3192-3e44-471d-87a4-9d91080809bb)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
