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
    return largedef max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



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
        if i>max:
            max=i
    return max



```


## Output:

i)	# To find the maximum of marks using the list method sort.
![maths1](https://user-images.githubusercontent.com/118787344/214769569-8e426236-fa95-4730-a8b9-ab9a48696131.png)


ii)	# To find the maximum marks using the list method max().
![maths2](https://user-images.githubusercontent.com/118787344/214769588-06aeaf6f-5858-4a4e-9dfc-c73eb23cdc98.png)


iii) # To find the maximum marks without using builtin functions.

![maths3](https://user-images.githubusercontent.com/118787344/214769603-69966e1f-9fc1-4dfa-9840-e03c1fb13a96.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
