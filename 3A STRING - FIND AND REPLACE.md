# Exp.No:3a
## STRING - String Slicing in Python


### AIM  
To write a Python program that extracts a part of a given string using slicing and displays the sliced substring.

### ALGORITHM
```
1.Start the program.
2.Define a function slice(a) that takes a string a as input.
3.Inside the function, use slicing a[2:7:1] to extract characters from index 2 to index 6.
4.Store the sliced part in the variable sliced.
5.Print the sliced string using print().
6.Call the function with a user-provided string.
7.End the program.
```

### PROGRAM

```
def slice(a):
    sliced=a[2:7:1]
    print(f"The sliced string is '{sliced}'")
```

### OUTPUT
<img width="1197" height="316" alt="image" src="https://github.com/user-attachments/assets/360d6bc1-344e-4ceb-b6a1-1ea9c3af35d2" />


### RESULT
The program successfully slices the given string from index 2 to 6 and displays the extracted substring.
