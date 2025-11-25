# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To Write a Python program to find sequences of lowercase letters joined with a underscore.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM
212223060181
NANCY CAROLEINE P R

```
import re

string = input()
pattern = r'^[a-z]+_[a-z]+$'

if re.match(pattern, string):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="598" height="200" alt="image" src="https://github.com/user-attachments/assets/3ddf9f06-14e5-4c49-9efc-aae29d56a43d" />


### RESULT
Thus  Python program to find sequences of lowercase letters joined with a underscore has been executed successfully.
