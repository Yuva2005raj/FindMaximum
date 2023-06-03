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

i) # To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: YUVARAJ B
RegisterNumber:212222230182 
'''

def max_marks(marks):
        marks.sort()
        large = marks[-1]
        return large

```

ii) # To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: YUVARAJ B
RegisterNumber: 212222230182
'''
def max_marks(marks):
    large=max(marks)
    return large
    
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    
    # write your code here
    max = list1[0]
    for i in list1:
         if i > max:
             max=i
    return max
    
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Yuva2005raj/FindMaximum/assets/118343998/e1bfbe48-bdf4-44e1-9469-2560907b6b24)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Yuva2005raj/FindMaximum/assets/118343998/4b9762cd-e1e3-4585-bca2-3b350a68a0af)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Yuva2005raj/FindMaximum/assets/118343998/e842d7ec-37e3-4867-9f1f-847ce313aa36)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
