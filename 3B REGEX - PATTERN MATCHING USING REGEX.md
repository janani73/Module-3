# Exp.No:3b  
## REGEX - Pattern Identification Using Python’s re Module



### AIM  
To write a Python program that determines whether a specific repeated-character pattern exists in the input string.

### ALGORITHM

```
1.Start the program.
2.Import the re module for pattern matching.
3.Accept an input string from the user.
4.Create a pattern ab{2,3} to match 'a' followed by 2 or 3 'b' characters.
5.Apply the re.search() function to locate the pattern.
6.If the pattern is matched, print a success message.
7.Otherwise, print a failure message.
8.End the program.
```

### PROGRAM

```
import re
a=input()
p=r"ab{2,3}"
if re.search(p,a):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="1193" height="312" alt="image" src="https://github.com/user-attachments/assets/3baa6b48-f2ad-4349-befb-2a4ec18e4c22" />

### RESULT
The program correctly detects the presence or absence of repeated-character patterns in the user-provided string.
