# 📘 README — Square Star Pattern Program (Python)

## 📌 Overview

This Python program prints a **square star (`*`) pattern** using nested loops.
Each row contains the same number of stars, forming a perfect square shape.

-------------------------------------------------------------------------

## ⚙️ Source Code

```python
n = 5

for i in range(1, n + 1):
    for j in range(1, n + 1):
        print("*", end=" ")
    print()
```

---

## 🧠 How It Works

### 1️⃣ Define Size of the Square

```python
n = 5
```

* Determines the number of rows and columns.
* Here, the program prints a **5 × 5 square**.

------------------------------------------------------

### 2️⃣ Outer Loop — Controls Rows

```python
for i in range(1, n + 1):
```

* Runs `n` times.
* Each iteration represents one row.

--------------------------------------------------------

### 3️⃣ Inner Loop — Prints Stars

```python
for j in range(1, n + 1):
    print("*", end=" ")
```

* Prints `n` stars in each row.
* `end=" "` keeps stars on the same line with spacing.

---

### 4️⃣ Move to Next Line

```python
print()
```

* Moves the cursor to the next row after printing a line of stars.

---

## ▶️ Sample Output

```
* * * * * 
* * * * * 
* * * * * 
* * * * * 
* * * * * 
```

----------------------------------------------------------

## 🎯 Key Concepts Demonstrated

* Nested loops
* Pattern printing logic
* Use of `range()` function
* Controlling output formatting with `end`

---

## 💡 Use Cases

This program is useful for:

* Learning nested loops
* Understanding 2D iteration logic
* Building a foundation for advanced pattern problems

---

## 🚀 Possible Enhancements

You can extend this program to create:

* Hollow square patterns
* Rectangle patterns
* Number squares
* Character patterns

---

## 👨‍💻 Author

Pranay Jadhao

-------------------------------------------------------------------------------------

<img width="687" height="705" alt="image" src="https://github.com/user-attachments/assets/b4a174b5-05ff-4313-95c6-b65866fb0b99" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------

