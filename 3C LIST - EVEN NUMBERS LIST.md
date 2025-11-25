# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To Write a python function that accepts N and to create a list with even numbers upto N, print the sum of all the elements in the list.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM
212223060181

NANCY CAROLEIENE P R
```
def createlist(n):
    l=[]
    for i in range(2,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```

### OUTPUT
<img width="797" height="241" alt="image" src="https://github.com/user-attachments/assets/e0962464-03ce-474e-98ad-5b969b0543b4" />

### RESULT
Thus a python function that accepts N and to create a list with even numbers upto N, print the sum of all the elements in the list has been executed successfully.
