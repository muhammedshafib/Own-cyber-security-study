Absolutely. I’ll combine **Tasks 1, 2, and 3** into one complete Python beginner study/practice set, including **explanations, syntax, example programs, practice questions, answers, and a final mini-project**.

# 🐍 Python Fundamentals — Tasks 1 to 3

## Complete Learning Roadmap

```text
TASK 1: Python Fundamentals
│
├── 1. Variables & Data Types
├── 2. Operators
├── 3. Input & Output
├── 4. Type Conversion
└── 5. Python Coding Practices
        ↓
TASK 2: Program Flow
│
├── 1. Conditional Statements
├── 2. Loops
├── 3. Nested Conditions
├── 4. Control Statements
└── 5. Problem-Solving Workflows
        ↓
TASK 3: Python Collections
│
├── 1. Lists
├── 2. Tuples
├── 3. Sets
├── 4. Dictionaries
└── 5. Collection Manipulation
```

---

# 🟢 TASK 1 — Understand Python Fundamentals

---

# 1. Variables and Data Types

## What is a variable?

A variable stores a value.

```python
name = "Shafi"
age = 22
```

Here:

```text
name → "Shafi"
age  → 22
```

## Common data types

| Type    | Example            | Meaning          |
| ------- | ------------------ | ---------------- |
| `str`   | `"Shafi"`          | Text             |
| `int`   | `22`               | Whole number     |
| `float` | `5.8`              | Decimal          |
| `bool`  | `True`             | True/False       |
| `list`  | `[1, 2, 3]`        | Collection       |
| `tuple` | `(1, 2, 3)`        | Fixed collection |
| `set`   | `{1, 2, 3}`        | Unique values    |
| `dict`  | `{"name":"Shafi"}` | Key-value        |

### Example

```python
name = "Shafi"
age = 22
height = 5.8
is_student = True

print(name)
print(age)
print(height)
print(is_student)
```

### Check type

```python
age = 22

print(type(age))
```

Output:

```text
<class 'int'>
```

---

# 2. Operators

## Arithmetic operators

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

Remember:

```text
+   Addition
-   Subtraction
*   Multiplication
/   Division
//  Floor division
%   Remainder
**  Power
```

## Comparison operators

```python
a = 10
b = 5

print(a == b)
print(a != b)
print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
```

Results are:

```text
True
False
```

## Logical operators

```python
age = 25

print(age >= 18 and age <= 60)
print(age < 18 or age > 60)
print(not age >= 18)
```

---

# 3. Input and Output

## Output

```python
print("Hello World")
```

## Input

```python
name = input("Enter your name: ")

print(f"Hello {name}")
```

Important:

```python
age = input("Enter age: ")
```

`age` is a **string**, even if you type `22`.

---

# 4. Type Conversion

Convert between data types.

```python
age = "22"

age = int(age)

print(age)
print(type(age))
```

Common conversions:

```python
int("10")
float("10.5")
str(100)
bool(1)
```

### Important program

```python
age = int(input("Enter your age: "))

print(f"Next year you will be {age + 1}")
```

---

# 5. Python Coding Practices

### Use meaningful names

❌

```python
x = 22
```

✅

```python
age = 22
```

### Use `snake_case`

```python
first_name = "Shafi"
student_age = 22
```

### Use indentation

```python
if age >= 18:
    print("Adult")
```

### Use comments

```python
# Store the user's age
age = 22
```

---

# 📝 TASK 1 — Questions and Answers

## Q1. Create variables for name, age and city.

### Answer

```python
name = "Shafi"
age = 22
city = "Chalakudy"

print(name)
print(age)
print(city)
```

---

## Q2. Take two numbers from the user and add them.

### Answer

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result = num1 + num2

print(f"Result: {result}")
```

---

## Q3. Calculate the area of a rectangle.

Formula:

```text
Area = length × width
```

### Answer

```python
length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print(f"Area = {area}")
```

---

## Q4. Find the remainder of two numbers.

### Answer

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print(a % b)
```

---

## Q5. What is the difference between `int` and `float`?

### Answer

```text
int   → whole numbers → 10, 20, 100
float → decimal numbers → 10.5, 20.75
```

---

# 🔵 TASK 2 — Understand Program Flow

Program flow controls **which code runs and how many times it runs**.

---

# 1. Conditional Statements

## `if`

```python
age = 20

if age >= 18:
    print("Adult")
```

## `if-else`

```python
age = 16

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

## `if-elif-else`

```python
marks = 85

if marks >= 90:
    print("A+")
elif marks >= 80:
    print("A")
elif marks >= 70:
    print("B")
else:
    print("Fail")
```

---

# 2. Loops

Loops repeat code.

## `for`

```python
for i in range(1, 6):
    print(i)
```

Output:

```text
1
2
3
4
5
```

## `while`

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

---

# 3. Nested Conditions

Condition inside another condition.

```python
age = 25
has_id = True

if age >= 18:
    if has_id:
        print("Access allowed")
    else:
        print("ID required")
else:
    print("Underage")
```

---

# 4. Control Statements

## `break`

Stops a loop.

```python
for i in range(1, 10):
    if i == 5:
        break

    print(i)
```

Output:

```text
1
2
3
4
```

## `continue`

Skips one iteration.

```python
for i in range(1, 6):
    if i == 3:
        continue

    print(i)
```

Output:

```text
1
2
4
5
```

## `pass`

Does nothing.

```python
if True:
    pass
```

---

# 5. Problem-Solving Workflow

When you receive a programming problem:

```text
1. Understand the problem
        ↓
2. Identify INPUT
        ↓
3. Identify OUTPUT
        ↓
4. Create the logic
        ↓
5. Write pseudocode
        ↓
6. Write Python
        ↓
7. Test
        ↓
8. Find errors
        ↓
9. Fix
```

---

# 📝 TASK 2 — Questions and Answers

## Q1. Check whether a number is positive, negative or zero.

### Answer

```python
number = int(input("Enter a number: "))

if number > 0:
    print("Positive")
elif number < 0:
    print("Negative")
else:
    print("Zero")
```

---

## Q2. Check whether a number is even or odd.

### Answer

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("Even")
else:
    print("Odd")
```

---

## Q3. Print numbers from 1 to 10.

### Answer

```python
for i in range(1, 11):
    print(i)
```

---

## Q4. Print only even numbers from 1 to 20.

### Answer

```python
for i in range(1, 21):
    if i % 2 == 0:
        print(i)
```

---

## Q5. Create a countdown from 10 to 1.

### Answer

```python
count = 10

while count >= 1:
    print(count)
    count -= 1

print("Done!")
```

---

## Q6. Create a simple login check.

### Answer

```python
username = input("Username: ")
password = input("Password: ")

if username == "admin":
    if password == "python123":
        print("Login successful")
    else:
        print("Wrong password")
else:
    print("Unknown username")
```

> This is only a learning example. Real applications should not hard-code or store passwords this way.

---

# 🟠 TASK 3 — Understand Python Collections

Collections allow you to store multiple values.

```text
List        → []
Tuple       → ()
Set         → {}
Dictionary  → {key: value}
```

---

# 1. Lists

Lists are:

* Ordered
* Mutable
* Allow duplicates
* Indexable

```python
names = ["Shafi", "Ali", "Ahmed"]

print(names[0])
print(names[1])
```

### Add

```python
names.append("Rahul")
```

### Change

```python
names[0] = "Muhammed"
```

### Remove

```python
names.remove("Ali")
```

### Loop

```python
for name in names:
    print(name)
```

---

# 2. Tuples

Tuples are **immutable**.

```python
coordinates = (10, 20)

print(coordinates[0])
```

You cannot normally do:

```python
coordinates[0] = 50
```

---

# 3. Sets

Sets store **unique values**.

```python
numbers = {10, 20, 30, 10, 20}

print(numbers)
```

Duplicates are automatically removed.

### Add

```python
numbers.add(40)
```

### Remove

```python
numbers.remove(20)
```

---

# 4. Dictionaries

Dictionary = **key → value**.

```python
student = {
    "name": "Shafi",
    "age": 22,
    "course": "Cyber Security"
}
```

Access:

```python
print(student["name"])
print(student["age"])
```

Add:

```python
student["city"] = "Kerala"
```

Change:

```python
student["age"] = 23
```

Loop:

```python
for key, value in student.items():
    print(key, value)
```

---

# 5. Collection Manipulation

## List length

```python
numbers = [10, 20, 30, 40]

print(len(numbers))
```

## Sorting

```python
numbers = [50, 10, 40, 20, 30]

numbers.sort()

print(numbers)
```

## Searching

```python
ports = [22, 80, 443]

if 443 in ports:
    print("Port found")
```

## Slicing

```python
numbers = [10, 20, 30, 40, 50]

print(numbers[1:4])
```

Output:

```text
[20, 30, 40]
```

---

# 📝 TASK 3 — Questions and Answers

## Q1. Create a list of five cybersecurity tools.

### Answer

```python
tools = ["Nmap", "Wireshark", "Burp Suite", "Metasploit", "Nikto"]

print(tools)
```

---

## Q2. Add a new tool.

### Answer

```python
tools.append("Gobuster")

print(tools)
```

---

## Q3. Remove a tool.

### Answer

```python
tools.remove("Nikto")

print(tools)
```

---

## Q4. Create a tuple containing an IP, port and protocol.

### Answer

```python
network_info = ("192.168.1.10", 443, "HTTPS")

print(network_info)
```

---

## Q5. Remove duplicate ports using a set.

### Answer

```python
ports = {22, 80, 443, 80, 443}

print(ports)
```

Result contains:

```text
22, 80, 443
```

---

## Q6. Create a dictionary containing username, role and status.

### Answer

```python
user = {
    "username": "shafi",
    "role": "student",
    "status": "active"
}

print(user)
```

---

## Q7. Print only ports greater than 100.

### Answer

```python
ports = [22, 80, 443, 8080, 21]

for port in ports:
    if port > 100:
        print(port)
```

Output:

```text
443
8080
```

---

# 🚀 FINAL COMBINED PROJECT

Now let's combine **all 3 tasks**.

## Project: Simple Security Information Analyzer

This project uses:

```text
Variables
Data types
Operators
Input
Output
Type conversion
if/elif/else
Loops
Lists
Sets
Dictionaries
Collection manipulation
```

### Question

Create a Python program that:

1. Asks for a username.
2. Asks for the user's age.
3. Stores some network ports in a list.
4. Removes duplicate ports using a set.
5. Checks the user's age.
6. Displays the user's information.
7. Checks whether port `443` exists.
8. Displays all ports greater than `100`.

### Answer

```python
# -----------------------------------
# Simple Security Information Analyzer
# -----------------------------------

# User information
username = input("Enter your username: ")
age = int(input("Enter your age: "))

# Network ports
ports = [22, 80, 443, 443, 8080, 21]

# Remove duplicate ports
unique_ports = set(ports)

# Store user information
user = {
    "username": username,
    "age": age
}

# Display user information
print("\n--- User Information ---")
print(f"Username: {user['username']}")
print(f"Age: {user['age']}")

# Age check
if age >= 18:
    print("Age status: Adult")
else:
    print("Age status: Minor")

# Display ports
print("\n--- Network Ports ---")
print(f"Original ports: {ports}")
print(f"Unique ports: {unique_ports}")

# Check HTTPS port
if 443 in unique_ports:
    print("HTTPS port 443 is present.")
else:
    print("HTTPS port 443 is not present.")

# Display ports greater than 100
print("\n--- Ports Greater Than 100 ---")

for port in unique_ports:
    if port > 100:
        print(port)
```

---

# 🧠 Understand How the Final Program Works

```text
                USER INPUT
                    ↓
          username + age
                    ↓
             VARIABLES
                    ↓
             DICTIONARY
                    ↓
             PORT LIST
                    ↓
             SET removes
             duplicates
                    ↓
             IF / ELSE
                    ↓
             AGE CHECK
                    ↓
               FOR LOOP
                    ↓
          CHECK EACH PORT
                    ↓
                OUTPUT
```

---

# 🎯 Final Practice Challenge

Try this **without looking at the answer first**.

### Question

Create a program for a small security log analyzer.

Given:

```python
ip_addresses = [
    "192.168.1.10",
    "10.0.0.5",
    "192.168.1.10",
    "172.16.0.5",
    "10.0.0.5"
]
```

Your program should:

1. Remove duplicate IP addresses.
2. Display the number of unique IPs.
3. Ask the user for an IP address.
4. Check whether that IP exists in the collection.
5. Display all unique IP addresses using a loop.

### Answer

```python
ip_addresses = [
    "192.168.1.10",
    "10.0.0.5",
    "192.168.1.10",
    "172.16.0.5",
    "10.0.0.5"
]

# Remove duplicates
unique_ips = set(ip_addresses)

# Display number of unique IPs
print(f"Unique IP count: {len(unique_ips)}")

# Ask the user for an IP
search_ip = input("Enter an IP address to search: ")

# Search IP
if search_ip in unique_ips:
    print("IP address found.")
else:
    print("IP address not found.")

# Display all unique IPs
print("\n--- Unique IP Addresses ---")

for ip in unique_ips:
    print(ip)
```

---

# 📚 Complete Revision Sheet

```text
TASK 1 — FUNDAMENTALS
────────────────────────
Variable       → stores a value
str            → text
int            → whole number
float          → decimal
bool           → True/False
input()        → receives input
print()        → displays output
int()          → converts to integer
float()        → converts to float
str()          → converts to string

TASK 2 — PROGRAM FLOW
────────────────────────
if             → decision
elif           → another condition
else           → otherwise
for            → repetition
while          → repetition while condition is true
break          → stop loop
continue       → skip iteration
pass           → do nothing

TASK 3 — COLLECTIONS
────────────────────────
List           → [] → ordered/changeable
Tuple          → () → ordered/immutable
Set            → {} → unique values
Dictionary     → {key:value} → key/value data

IMPORTANT METHODS
────────────────────────
list.append()
list.remove()
list.pop()
list.sort()
list.reverse()
len()
set.add()
set.remove()
dict.items()
```

## 🏆 What you should be able to do now

After Tasks **1–3**, you should be able to write a small Python program from scratch using:

**Input → Variables → Type Conversion → Conditions → Loops → Collections → Output**

That is the foundation you need before moving into **functions, modules, files, exceptions, and eventually cybersecurity automation with Python**.
