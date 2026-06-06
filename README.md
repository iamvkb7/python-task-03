# Python Internship Program — Task 3

## Functions & Code Reusability

### 🌟 Overview

This repository contains Python programs developed as part of **Task 3** of the Python Internship Program. The objective of this task is to understand Python functions and their role in creating reusable, organized, and maintainable code.

The task covers function creation, parameters, arguments, return values, recursion, lambda functions, variable scope, and functional programming concepts through practical implementations.

### 🎯 Learning Objectives

* Understand function definition and scope
* Work with parameters and arguments
* Use return statements effectively
* Learn default arguments
* Implement variable-length arguments using `*args`
* Understand lambda functions
* Learn recursion concepts
* Understand local, global, and nonlocal variables
* Improve code reusability through modular programming

### 📚 Concepts Covered

#### 1. Function Definition

A function is a reusable block of code that performs a specific task. Functions reduce code duplication and improve program organization.

Example:

```python
def greet():
    print("Hello")
```

#### 2. Parameters and Arguments

Parameters are variables defined in a function, while arguments are the values passed during a function call.

Example:

```python
def greet(name):
    print("Hello", name)

greet("Vimal")
```

#### 3. Return Values

Functions can return data using the `return` statement.

Example:

```python
def add(a, b):
    return a + b

result = add(5, 10)
```

#### 4. Default Arguments

Default arguments provide a value when no argument is supplied.

Example:

```python
def greet(name="User"):
    print("Hello", name)
```

#### 5. Variable-Length Arguments (*args)

`*args` allows a function to accept multiple inputs.

Example:

```python
def add_numbers(*args):
    return sum(args)
```

#### 6. Lambda Functions

Lambda functions are anonymous, single-line functions.

Example:

```python
square = lambda x: x * x
```

#### 7. Recursion

Recursion occurs when a function calls itself.

Example:

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)
```

#### 8. Variable Scope

Python supports:

* Local Variables
* Global Variables
* Nonlocal Variables

#### 9. Code Reusability

Functions allow developers to write code once and use it multiple times, making programs more efficient and maintainable.

### 💻 Programs Implemented

#### 1. BMI Calculator

Calculates Body Mass Index and determines health status.

#### 2. EMI Calculator

Computes monthly EMI based on loan amount, interest rate, and tenure.

#### 3. Recursive Factorial Program

Calculates factorial using recursion.

#### 4. Fibonacci Series Generator

Generates Fibonacci numbers using functions and loops.

#### 5. Prime Number Checker

Checks whether a given number is prime.

#### 6. map(), filter(), and reduce() Demo

Demonstrates functional programming concepts in Python.

### 📁 File Structure

```
Task-3/
│
├── bmi_calculator.py
├── emi_calculator.py
├── factorial_recursion.py
├── fibonacci.py
├── prime_checker.py
├── map_filter_reduce.py
├── default_arguments.py
├── args_example.py
├── lambda_example.py
├── variable_scope.py
└── README.md
```

### 🧠 Key Takeaways

* Functions improve code organization.
* Parameters and return values make functions flexible.
* Recursion helps solve repetitive problems elegantly.
* Lambda functions provide concise syntax.
* Variable scope controls accessibility of data.
* Functional programming techniques simplify data processing.
* Code reusability reduces development time and maintenance effort.

### ✅ Conclusion

This task provided practical experience with Python functions and demonstrated how they contribute to writing clean, efficient, and reusable code. Understanding functions is essential for developing scalable and professional Python applications.

### 👨‍💻 Author

**Vimal kumar**

Python Internship Program — Task 3
