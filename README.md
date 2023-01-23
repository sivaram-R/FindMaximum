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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: sivaram R
RegisterNumber: 22008680
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: sivaram R
RegisterNumber: 22008680
'''
def max_marks(marks):
    # write your code here
    large =max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: sivaram R
RegisterNumber: 22008680
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
1.![max](https://user-images.githubusercontent.com/121165794/214008969-01fdf21b-1c8a-4efb-8146-6c6902d3f5cc.png)
2.![max2](https://user-images.githubusercontent.com/121165794/214009028-776aa31b-a1e9-4691-a58c-14b6651d31bd.png)
3.![max3](https://user-images.githubusercontent.com/121165794/214009075-c3c40e2b-7bc1-41a5-b055-70bbf45789ea.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
