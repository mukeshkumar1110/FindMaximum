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
    max_marks=max(marks)
    return max_marks
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max
```



## Output:
i)

![image](https://github.com/durgadevi22d/FindMaximum/assets/149987216/1936bdd5-7523-48b1-9b79-c8fb57cc271f)


ii)

![image](https://github.com/durgadevi22d/FindMaximum/assets/149987216/4903ea4b-e64d-4dd2-a22c-be8186b8dbcd)


iii)

![image](https://github.com/durgadevi22d/FindMaximum/assets/149987216/f352c1f1-3c4f-4e61-8fe9-dade4cd27b38)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
