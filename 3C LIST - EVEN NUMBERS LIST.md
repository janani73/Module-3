# Exp.No:3c
## LIST - Creating and Displaying a List Using User Inputs in Python



### AIM  
To write a Python program that accepts multiple values from the user, stores them in a list, and displays the final list.

### ALGORITHM

```
1.Start the program.
2.Read the list size using size = int(input()).
3.Create an empty list l = [].
4.Repeat steps for size number of times:
5.Take an input from the user using eval(input()).
6.Append the value to the list using l.append(item).
7.After the loop, print the final list using print(l).
8.End the program.
```

### PROGRAM

```
size=int(input())
l=[]
for i in range(0,size):
    item=eval(input())
    l.append(item)
print(l)  
```

### OUTPUT
<img width="1185" height="431" alt="image" src="https://github.com/user-attachments/assets/44d2db4b-ad17-42be-ba05-e038e91584a8" />


### RESULT
The program successfully accepts different types of user inputs (numbers, lists, tuples, strings, etc., using eval) and stores them inside a list, which is then displayed.
