# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
# Start the program

rows = int(input())

for n in range(rows):
    # Print spaces
    print(" " * (rows - n), end="")

    value = 1
    for k in range(n + 1):
        print(value, end=" ")
        value = value * (n - k) // (k + 1)

    print()

```
## Sample Output
<img width="271" height="185" alt="image" src="https://github.com/user-attachments/assets/9f9b5e45-9df7-40ac-93f0-2d31eafa60e8" />

## Result
Thus the code rann succesfully and got the output
