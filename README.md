# Find the maximum of a list of numbers

Developed by:Mahasri P

Register no: 212223100029

Dept:AIDS

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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark


```



## Output:
i)

![image](https://github.com/PreethiS647/FindMaximum/assets/147313372/031616ee-2bf0-4263-bf4e-ca151943e352)

ii)

![image](https://github.com/PreethiS647/FindMaximum/assets/147313372/94ac8560-ca95-471a-a825-405d680ca118)

iii)

![image](https://github.com/PreethiS647/FindMaximum/assets/147313372/5fee53df-77e4-429a-96b4-a9345e9e375f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
