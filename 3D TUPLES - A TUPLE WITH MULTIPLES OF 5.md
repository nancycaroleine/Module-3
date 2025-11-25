# Exp.No:3d  
## TUPLES - join tuples

---

### AIM  
To Write a python program to join tuples if similar initial  element**N**.

---

### ALGORITHM
1. Begin the program.
2. Initialize a list of tuples.
3. Display the initial list.
4. Create an empty dictionary named grouped.
5. For each tuple t in the list:
   5.1 Extract the first element of t as the key.
   5.2 If the key is not in grouped:
       5.2.1 Add key to grouped with list(t) as its value.
   5.3 Else:
       5.3.1 Extend the existing value of grouped[key] with the remaining elements of t.
6. Convert each value in grouped back to a tuple.
7. Store the converted tuples in a list named result.
8. Display the final joined list.
9. End the program.


---

### PROGRAM
212223060181

NANCY CAROLEINE P R
```
tuple_list = [(2, 5), (9, 4), (9, 0), (1, 4), (1, 5)]

print("Initially the list is :", tuple_list)

# Dictionary to group tuples by their first element
grouped = {}

for t in tuple_list:
    key = t[0]
    if key not in grouped:
        grouped[key] = list(t)
    else:
        grouped[key].extend(t[1:])  # Append the rest of the tuple

# Convert grouped values back to tuples
result = [tuple(value) for value in grouped.values()]

print("Joined list :", result)

```

### OUTPUT
<img width="1151" height="167" alt="image" src="https://github.com/user-attachments/assets/05368d71-8f88-44f5-a565-30dee07c509b" />

### RESULT
Thus a python program to join tuples if similar initial  element has been executed successfully
