# Python Function-Based Examples --- 15 Programs

Beginner-friendly Python programs focused on **functions**, parameters,
return values, conditions, loops, and basic operators.

------------------------------------------------------------------------

## 1. Function to Add Two Numbers

### Program

``` python
def add(a, b):
    return a + b

result = add(10, 20)
print("Addition:", result)
```

### Concept

-   Function definition
-   Parameters
-   `return`
-   Arithmetic operator `+`

------------------------------------------------------------------------

## 2. Function to Subtract Two Numbers

``` python
def subtract(a, b):
    return a - b

result = subtract(20, 8)
print("Subtraction:", result)
```

### Concept

-   Parameters
-   Return value
-   `-` operator

------------------------------------------------------------------------

## 3. Function to Multiply Two Numbers

``` python
def multiply(a, b):
    return a * b

result = multiply(5, 6)
print("Multiplication:", result)
```

### Concept

-   Function
-   Parameters
-   `*` operator

------------------------------------------------------------------------

## 4. Function to Divide Two Numbers

``` python
def divide(a, b):
    if b == 0:
        return "Cannot divide by zero"
    return a / b

result = divide(20, 5)
print("Division:", result)
```

### Concept

-   Function
-   `if` condition
-   `return`
-   `/` operator

------------------------------------------------------------------------

## 5. Function to Check Even or Odd

``` python
def check_even_odd(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"

result = check_even_odd(15)
print(result)
```

### Concept

-   Function
-   `if/else`
-   Modulus `%`
-   Comparison `==`

------------------------------------------------------------------------

## 6. Function to Find Largest of Two Numbers

``` python
def largest(a, b):
    if a > b:
        return a
    else:
        return b

result = largest(50, 30)
print("Largest:", result)
```

### Concept

-   Function parameters
-   `if/else`
-   Comparison operator `>`

------------------------------------------------------------------------

## 7. Function to Find Largest of Three Numbers

``` python
def largest_of_three(a, b, c):
    if a >= b and a >= c:
        return a
    elif b >= a and b >= c:
        return b
    else:
        return c

result = largest_of_three(25, 50, 35)
print("Largest:", result)
```

### Concept

-   Multiple parameters
-   `if/elif/else`
-   `and`
-   Comparison operators

------------------------------------------------------------------------

## 8. Function to Calculate Square

``` python
def square(number):
    return number * number

result = square(7)
print("Square:", result)
```

### Concept

-   Function
-   Parameter
-   Return value
-   Multiplication

------------------------------------------------------------------------

## 9. Function to Calculate Factorial

``` python
def factorial(number):
    result = 1

    for i in range(1, number + 1):
        result = result * i

    return result

print("Factorial:", factorial(5))
```

### Concept

-   Function
-   `for` loop
-   `range()`
-   Multiplication
-   Return value

------------------------------------------------------------------------

## 10. Function to Calculate Simple Interest

Formula:

`Simple Interest = (Principal × Rate × Time) / 100`

``` python
def simple_interest(principal, rate, time):
    interest = (principal * rate * time) / 100
    return interest

result = simple_interest(10000, 5, 2)
print("Simple Interest:", result)
```

### Concept

-   Function
-   Multiple parameters
-   Arithmetic operators
-   Formula implementation

------------------------------------------------------------------------

## 11. Function to Check Voting Eligibility

``` python
def check_voting(age):
    if age >= 18:
        return "Eligible for voting"
    else:
        return "Not eligible for voting"

print(check_voting(22))
```

### Concept

-   Function
-   Condition
-   `>=`
-   Return value

------------------------------------------------------------------------

## 12. Function to Calculate Student Grade

``` python
def get_grade(marks):
    if marks >= 90:
        return "A"
    elif marks >= 75:
        return "B"
    elif marks >= 60:
        return "C"
    elif marks >= 40:
        return "D"
    else:
        return "Fail"

print("Grade:", get_grade(82))
```

### Concept

-   Function
-   `if/elif/else`
-   Comparison operators
-   Return value

------------------------------------------------------------------------

## 13. Function to Calculate Area of a Rectangle

Formula:

`Area = Length × Width`

``` python
def rectangle_area(length, width):
    return length * width

area = rectangle_area(10, 5)
print("Rectangle Area:", area)
```

### Concept

-   Function
-   Parameters
-   Arithmetic operation
-   Return value

------------------------------------------------------------------------

## 14. Function to Count Vowels

``` python
def count_vowels(text):
    count = 0

    for character in text.lower():
        if character in "aeiou":
            count = count + 1

    return count

result = count_vowels("Python Programming")
print("Number of vowels:", result)
```

### Concept

-   Function
-   String
-   `for` loop
-   `if`
-   `in`
-   String method `lower()`

------------------------------------------------------------------------

## 15. Function-Based Simple Calculator

``` python
def calculator(a, b, operator):
    if operator == "+":
        return a + b

    elif operator == "-":
        return a - b

    elif operator == "*":
        return a * b

    elif operator == "/":
        if b == 0:
            return "Cannot divide by zero"
        return a / b

    else:
        return "Invalid operator"


a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
operator = input("Enter operator (+, -, *, /): ")

result = calculator(a, b, operator)

print("Result:", result)
```

### Concept

-   Function
-   Parameters
-   `if/elif/else`
-   Arithmetic operators
-   User input
-   Return values

------------------------------------------------------------------------

# Function Concepts Covered

  \#   Example           Main Function Concept
  ---- ----------------- -----------------------
  1    Addition          Parameters + return
  2    Subtraction       Parameters + return
  3    Multiplication    Parameters + return
  4    Division          Function + condition
  5    Even/Odd          Function + `%`
  6    Largest of 2      Comparison
  7    Largest of 3      Multiple conditions
  8    Square            Return value
  9    Factorial         Function + loop
  10   Simple Interest   Formula + parameters
  11   Voting            Function + condition
  12   Grade             `if/elif/else`
  13   Rectangle Area    Function + formula
  14   Count Vowels      Function + loop
  15   Calculator        Function + operators

# Important Python Function Syntax

``` python
def function_name(parameters):
    # function body
    return value
```

### Example

``` python
def add(a, b):
    return a + b

answer = add(10, 20)
print(answer)
```

### Key Terms

-   `def` --- creates a function
-   Function name --- identifies the function
-   Parameter --- input received by a function
-   Argument --- actual value passed to a function
-   `return` --- sends a result back
-   Function call --- executes the function
