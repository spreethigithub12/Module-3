# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.


### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.


### PROGRAM

```
#Reg.No: 212222060182
#Name: Preethika S

import re
a=input()
x=re.findall(r".{2,3}b",a)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="690" height="192" alt="image" src="https://github.com/user-attachments/assets/111de1a5-a0a6-40e5-aedf-ba717c5ece84" />

### RESULT
This program for string containing an 'a' followed by two to three 'b' characters using regular expression is successfully executed.
