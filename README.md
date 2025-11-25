# PR.1-Fundamental-Booster

## 1. Introduction

This document explains the **core Python fundamentals** required for the Python Fundamental Booster Project. It covers essential concepts such as `print()`, `input()`, variables, data types, operators, type casting, constructors, and built‑in functions like `id()` and `type()`.

## 2. print() Function
The `print()` function is used to display output on the screen.

### Example:

```python
print("Hello, Python!")
print("Sum:", 10 + 20)

## 3. input() Function
The `input()` function is used to take user input. It always returns a **string**.

### Example:

```python
name = input("Enter your name: ")
print("Welcome", name)

## 4. Variables
Variables are containers used to store values. Python does not require explicit declaration of variable types.

### Example:

```python
x = 10
name = "Prince"

## 5. Data Types
Common Python data types:

* **int** → whole numbers
* **float** → decimal numbers
* **str** → text values
* **bool** → True/False
* **list** → ordered, changeable collection
* **tuple** → ordered, unchangeable collection
* **dict** → key-value data structure

### Example:

```python
age = 20
pi = 3.14
is_student = True
marks = [85, 90, 78]

## 6. Operators
### 6.1 Arithmetic Operators

`+  -  *  /  %  //  **`

```python
print(10 + 5)
print(10 // 3)
```
### 6.2 Comparison Operators
`== != > < >= <=`
```python
print(10 > 3)
```
### 6.3 Logical Operators

`and  or  not`

```python
print(5 > 2 and 3 < 1)
```
## 7. Type Casting
Convert one data type into another.

### Example:

```python
num = int("25")
f = float("3.14")
text = str(100)

## 8. Constructor (**init**)
In Python, a constructor is created using the `__init__()` method inside a class. It runs automatically when an object is created.

### Example:

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

s1 = Student("Prince", 20)
print(s1.name)

## 9. type() Function
Returns the data type of a variable.

### Example:
```python
x = 50
print(type(x))  # <class 'int'>

## 10. id() Function
Returns the unique memory address of an object.

### Example:

```python
x = 10
y = 10
print(id(x))
print(id(y))

## 11. Program Flow

The Python Fundamental Booster Project follows a simple and clear program structure:

### 11.1 Welcome and Instructions

* Display a welcome message.
* Show instructions for the user.

```python
print("Welcome to the Python Fundamental Booster Project!")
print("Follow the instructions and enter the required details.")
```

### 11.2 Collect Information

* Use `input()` to collect user details.

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
```

### 11.3 Data Processing

* Process data using variables, operators, and type casting.

```python
years_after = age + 5
```

### 11.4 Display Result

* Use `print()` to display messages and output.

```python
print("Hello", name)
print("After 5 years, your age will be:", years_after)
```

### 11.5 Exit Message

```python
print("Thank you for using the Python Fundamental Booster Project!")
```

## 12. Conclusion

These fundamental concepts form the foundation of the Python Fundamental Booster Project. Mastering them will help you progress confidently into loops, functions, data structures, and more advanced Python topics.
