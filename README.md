# Python Crash Course

A companion repository for a hands-on **Python Crash Course** — lessons, simple examples, and assignments designed to help every student understand Python easily.

---

## Lesson 1 — Introduction to Python

### 🎯 Objective

Learn what Python is and how to start writing basic programs.

---

### 📘 Key Definitions

**1. Python:** A simple and powerful programming language used for web development, data science, AI, and automation.

**2. Syntax:** The rules that define how to write correct Python code.

**3. Comment:** A note written in the code for explanation. It starts with `#` and is ignored by Python.

**4. Variable:** A name that stores data or a value. Example: `x = 10`

**5. Data Type:** The kind of value a variable holds — such as a number, text, or true/false.

**6. Input Function:** Used to take information from the user. Example: `input("Enter your name:")`

**7. Output Function:** Used to show information on the screen. Example: `print("Hello!")`

**8. Indentation:** Spaces at the beginning of a line to define code blocks.

---

### 📖 Lesson Explanation

#### Example 1 — Print a Message

```python
print("Hello, Python!")
```

This prints a message on the screen.

#### Example 2 — Variables

```python
name = "Abdalla"
age = 19
print("My name is", name, "and I am", age, "years old.")
```

Variables store data like text or numbers.

#### Example 3 — Taking Input from the User

```python
user_name = input("Enter your name: ")
print("Welcome,", user_name)
```

The `input()` function allows users to type and give information to your program.

#### Example 4 — Simple Math

```python
a = 5
b = 3
print("Sum:", a + b)
print("Product:", a * b)
```

You can use operators like `+`, `-`, `*`, and `/` to do math in Python.

---

## Lesson 2 — Control Statements

### 🎯 Objective

Learn how to make decisions in Python using `if`, `elif`, and `else`.

---

### 📘 Key Definitions

**1. Control Statement:** Allows your program to make decisions.

**2. Condition:** A statement that checks if something is true or false.

**3. If Statement:** Runs code only when a condition is true.

**4. Elif Statement:** Runs another condition if the previous one was false.

**5. Else Statement:** Runs code when no condition is true.

---

### 📖 Lesson Explanation

#### Example 1 — Positive or Negative Number

```python
number = float(input("Enter a number: "))

if number > 0:
    print("The number is positive.")
elif number < 0:
    print("The number is negative.")
else:
    print("The number is zero.")
```

This program checks if a number is positive, negative, or zero.

#### Example 2 — Even or Odd

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

The `%` symbol (modulus) checks the remainder when dividing by 2.

#### Example 3 — Age Category

```python
age = int(input("Enter your age: "))

if age < 13:
    print("You are a Child.")
elif age < 20:
    print("You are a Teenager.")
else:
    print("You are an Adult.")
```

This program uses multiple conditions to check the age group.

---

### 🧮 Assignments

#### Assignment 1 — Greeting Program

Ask the user to enter their name and age, then display a message:

```
Hello Abdalla! You are 19 years old.
```

#### Assignment 2 — Simple Calculator

Ask the user to enter two numbers and show the results of addition, subtraction, multiplication, and division.

#### Assignment 3 — Number Sign Checker

Write a program that asks for a number and prints if it is positive, negative, or zero.

#### Assignment 4 — Even or Odd

Write a program that asks for a number and tells if it’s even or odd.

---

✅ **Next Lesson:** Loops and Repetition Statem
