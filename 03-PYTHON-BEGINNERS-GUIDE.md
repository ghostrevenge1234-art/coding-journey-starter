# 🐍 Python Beginner's Guide

Python is the perfect first programming language - it reads almost like English!

## Why Python?

✅ Easy to read and learn
✅ Widely used in industry
✅ Great for web, data science, automation
✅ Huge community and resources

---

## Python Basics

### 1. Your First Program

Create a file called `hello.py`:

```python
print("Hello, World!")
```

Run it:
```bash
python hello.py
```

### 2. Variables & Data Types

```python
# Variables store information
name = "Alice"
age = 25
height = 5.6
is_student = True

# Data types
string = "text"
integer = 42
float_num = 3.14
boolean = True
```

### 3. Basic Operations

```python
# Math
result = 10 + 5
result = 10 - 3
result = 10 * 2
result = 10 / 2

# Strings
full_name = "John" + " " + "Doe"
repeated = "Ha" * 3  # "HaHaHa"
```

### 4. Getting Input from User

```python
name = input("What's your name? ")
age = input("How old are you? ")

print(f"Hello {name}, you are {age} years old!")
```

### 5. Conditionals (If/Else)

```python
age = 18

if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")

# Multiple conditions
if age < 13:
    print("Child")
elif age < 18:
    print("Teen")
else:
    print("Adult")
```

### 6. Loops

```python
# For loop
for i in range(5):
    print(i)  # Prints 0, 1, 2, 3, 4

# While loop
count = 0
while count < 5:
    print(count)
    count = count + 1

# Loop through list
fruits = ["apple", "banana", "orange"]
for fruit in fruits:
    print(fruit)
```

### 7. Lists

```python
# Create a list
fruits = ["apple", "banana", "orange"]
numbers = [1, 2, 3, 4, 5]

# Access items (starts at 0)
first_fruit = fruits[0]  # "apple"

# Add items
fruits.append("grape")

# Remove items
fruits.remove("banana")

# Length
print(len(fruits))  # 3
```

### 8. Dictionaries

```python
# Store key-value pairs
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}

# Access values
print(person["name"])  # Alice

# Add/update
person["job"] = "Developer"
```

### 9. Functions

```python
# Define a function
def greet(name):
    return f"Hello, {name}!"

# Call the function
message = greet("Alice")
print(message)  # "Hello, Alice!"

# Function with multiple parameters
def add(a, b):
    return a + b

result = add(5, 3)  # 8
```

### 10. Comments

```python
# This is a comment
print("This runs")  # Comments explain code

"""This is a multi-line comment
Useful for longer explanations"""
```

---

## Practice Exercises

### Exercise 1: Calculator
Create a program that:
- Asks user for two numbers
- Asks what operation (+, -, *, /)
- Prints the result

### Exercise 2: Grade Calculator
Create a program that:
- Asks for a student's score (0-100)
- Returns their grade (A, B, C, D, F)

### Exercise 3: Number Guessing Game
Create a program that:
- Picks a random number (1-100)
- User tries to guess it
- Give hints ("too high" or "too low")

---

## Resources for Practice

- **Codecademy**: Interactive Python lessons
- **LeetCode**: Coding challenges
- **HackerRank**: More practice problems
- **Real Python**: Detailed tutorials

---

## Next Steps

→ Move to: **[Learning Resources](./04-LEARNING-RESOURCES.md)**
