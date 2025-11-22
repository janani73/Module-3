# Exp.No:3e
## SEB -Matching Uppercase Letter Patterns Using Regular Expressions in Python

### AIM  
To write a Python program that checks whether a given string contains a pattern of uppercase letters followed by an underscore and one or more uppercase letters using regular expressions.

### ALGORITHM

```
1.Start the program.
2.Import the re module for regular expression operations.
3.Take an input string from the user and store it in variable s.
4.Define the regex pattern:
  r'[A-Z]*_[A-Z]+'
 This represents:
    A-Z* → zero or more uppercase letters
    _ → an underscore
    A-Z+ → one or more uppercase letters
5.Use re.search(pattern, s) to check if the input string matches the pattern.
6.If a match is found, print "Found a match!".
7.Otherwise, print "Not matched!".
8.End the program.
```

### PROGRAM

```
import re
s=input()
pattern=r'[A-Z]*_[A-Z]+'
if re.search(pattern,s):
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
<img width="1172" height="312" alt="image" src="https://github.com/user-attachments/assets/5dacaaa6-8032-46ae-b2c6-0b11798d00f5" />


### RESULT
