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
Program to mark the maximum of marks using the list method sort
Developed by: Sana Fathima H
RegisterNumber:212223240145

def max_marks(marks):
    marks.sort()
    highest=marks[-1]
    return highest
 ```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Sana Fathima H
RegisterNumber:212223240145
'''
def max_marks(marks):
    marks1=max(marks)
    return marks1
```
iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Sana Fathima H
RegisterNumber: 212223240145
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```



## Output:
![image](https://github.com/Sanafathima95773/FindMaximum/assets/147084627/26f104d7-c707-407e-b0af-f26625e5c3d2)
![image](https://github.com/Sanafathima95773/FindMaximum/assets/147084627/bf6e956f-7952-4881-bbb3-350107933235)
![image](https://github.com/Sanafathima95773/FindMaximum/assets/147084627/50b5ee74-ab25-43ef-9ef7-587304561c7a)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
