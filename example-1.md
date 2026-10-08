Absolutely. Here are **15 basic Python programs** focused on **operators and control statements**, suitable for beginners/practice.

### 1. Add Two Numbers

```python
a = 10
b = 20

result = a + b

print("Addition:", result)
```

**Operator:** `+`

---

### 2. Check Even or Odd

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

**Operators:** `%`, `==`  
**Control:** `if`, `else`

---

### 3. Check Positive, Negative or Zero

```python
num = int(input("Enter a number: "))

if num > 0:
    print("Positive")
elif num < 0:
    print("Negative")
else:
    print("Zero")
```

**Operators:** `>`, `<`  
**Control:** `if`, `elif`, `else`

---

### 4. Find Largest of Two Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

if a > b:
    print("First number is largest")
else:
    print("Second number is largest")
```

**Operator:** `>`

---

### 5. Find Largest of Three Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b and a > c:
    print("A is largest")
elif b > a and b > c:
    print("B is largest")
else:
    print("C is largest")
```

**Operators:** `>`, `and`

---

### 6. Simple Calculator

```python
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
op = input("Enter operator (+, -, *, /): ")

if op == "+":
    print(a + b)
elif op == "-":
    print(a - b)
elif op == "*":
    print(a * b)
elif op == "/":
    print(a / b)
else:
    print("Invalid operator")
```

**Operators:** `+`, `-`, `*`, `/`, `==`

---

### 7. Check Voting Eligibility

```python
age = int(input("Enter your age: "))

if age >= 18:
    print("You can vote")
else:
    print("You cannot vote")
```

**Operator:** `>=`

---

### 8. Check Pass or Fail

```python
marks = int(input("Enter marks: "))

if marks >= 40:
    print("Pass")
else:
    print("Fail")
```

**Operator:** `>=`

---

### 9. Student Grade

```python
marks = int(input("Enter marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
elif marks >= 40:
    print("Grade D")
else:
    print("Fail")
```

**Operator:** `>=`

---

### 10. Print Numbers 1 to 10

```python
for i in range(1, 11):
    print(i)
```

**Control:** `for` loop

---

### 11. Print Even Numbers

```python
for i in range(1, 21):
    if i % 2 == 0:
        print(i)
```

**Operators:** `%`, `==`  
**Control:** `for`, `if`

---

### 12. Print Multiplication Table

```python
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
```

**Operator:** `*`  
**Control:** `for`

---

### 13. Sum of Numbers Using `while`

```python
num = 1
total = 0

while num <= 10:
    total = total + num
    num = num + 1

print("Total:", total)
```

**Operators:** `+`, `<=`  
**Control:** `while`

---

### 14. Check Leap Year

```python
year = int(input("Enter year: "))

if year % 400 == 0:
    print("Leap Year")
elif year % 100 == 0:
    print("Not a Leap Year")
elif year % 4 == 0:
    print("Leap Year")
else:
    print("Not a Leap Year")
```

**Operators:** `%`, `==`  
**Control:** `if`, `elif`, `else`

---

### 15. Login System

```python
username = input("Enter username: ")
password = input("Enter password: ")

if username == "admin" and password == "12345":
    print("Login Successful")
else:
    print("Invalid username or password")
```

**Operators:** `==`, `and`  
**Control:** `if`, `else`

---

### Topics covered

| # | Program | Main Concept |
|---|---|---|
| 1 | Addition | Arithmetic operator |
| 2 | Even/Odd | `%`, `if` |
| 3 | Positive/Negative | `if/elif/else` |
| 4 | Largest of 2 | Comparison |
| 5 | Largest of 3 | `and` |
| 6 | Calculator | Operators + conditions |
| 7 | Voting | `>=` |
| 8 | Pass/Fail | Condition |
| 9 | Grade | Multiple conditions |
| 10 | 1–10 Numbers | `for` |
| 11 | Even Numbers | Loop + `%` |
| 12 | Table | Loop + multiplication |
| 13 | Sum | `while` |
| 14 | Leap Year | `%` + conditions |
| 15 | Login | `and` + conditions |

These 15 examples cover the basic **Python operators** (`+ - * / % > < >= <= == !=`, `and`) and **control statements** (`if`, `elif`, `else`, `for`, `while`).
