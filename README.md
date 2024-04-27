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
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## Output:
![Screenshot 2024-04-02 133506](https://github.com/Sabari-2005/FindMaximum/assets/139338709/9141c85c-222b-4d74-9b3f-f11c96584b17)
![Screenshot 2024-04-02 133524](https://github.com/Sabari-2005/FindMaximum/assets/139338709/a08ecb05-d003-4abb-8ccc-f2337b00a405)
![Screenshot 2024-04-02 133535](https://github.com/Sabari-2005/FindMaximum/assets/139338709/fd3deed0-de87-49c4-81d8-8f0f29f3ca71)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
