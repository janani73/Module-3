# Exp.No:3d  
## TUPLES -Repetition Operation on Tuples in Python

### AIM  
To write a Python program that takes a tuple and a number as input, repeats the tuple the given number of times, and displays the final result.

### ALGORITHM

```
1.Start the program.
2.Define a function repeat_tuple().
3.Inside the function, take the first input using eval(input()) and store it in item.
4.Take another input using int(input()) and store it in n.
5.Multiply the tuple using result = item * n.
6.Print the repeated tuple.
7.Call the function repeat_tuple() to execute the program.
8.End the program.
```

### PROGRAM

```
def repeat_tuple():
    item=eval(input())
    n=int(input())
    result=item*n
    print(result)
repeat_tuple()
```

### OUTPUT
<img width="1188" height="350" alt="image" src="https://github.com/user-attachments/assets/eebbc7d2-3253-4454-af91-c225f54841ef" />


### RESULT
The program successfully repeats the input tuple n times and prints the resulting expanded tuple.
