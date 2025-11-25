# Exp.No:3a
## STRING - FIND the frequency of the character

---

### AIM  
To write a the  python program to find the frequency of the character 'L' from the  string "Life is to Live".

---

### ALGORITHM

1. Begin the program.
2. Define a function that accepts two arguments: inp_str and char.
3. Inside the function, check if the length of char is not equal to 1.
   3.1 If true, display "Please enter a single character" and return.
4. Count the frequency of char in inp_str using count().
5. Display the frequency with a proper message.
6. Read a string input from the user and store it in inp_str.
7. Read a character input from the user and store it in char.
8. Call the function with inp_str and char.
9. End the program.


---

### PROGRAM

```
212223060181
NANCY CAROLEINE P R
def char_str(inp_str,char):
    if len (char)!=1:
        print("Please enter a single character")
        return
    freq=inp_str.count(char)
    print(f"Character {char} in the {inp_str} is {freq} times")
inp_str=input()
char=input()
char_str(inp_str,char)
```

### OUTPUT
<img width="1143" height="317" alt="image" src="https://github.com/user-attachments/assets/aab59616-b363-4264-9352-18206bec2b45" />

### RESULT
Thus the  python program to find the frequency of the character 'L' from the  string "Life is to Live" has been excuted successfully.
