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

![Screenshot 2024-04-10 192750](https://github.com/mahasri06/FindMaximum/assets/139841897/c85545bd-743b-4b30-a1d8-92620b787c99)


ii)
![Screenshot 2024-04-10 192807](https://github.com/mahasri06/FindMaximum/assets/139841897/7e6a886d-0784-47e2-8ef0-e3ba9ea79eb2)


iii)

![Screenshot 2024-04-10 192820](https://github.com/mahasri06/FindMaximum/assets/139841897/5dac2dba-5d85-4b88-abca-18eb51e6994e)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
