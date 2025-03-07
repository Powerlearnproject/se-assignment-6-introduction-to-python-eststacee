[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15343151&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   - Python is a high-level, interpreted programming language that is widely used for many different purposes. Some key features include; readable syntax, interpreted language and cross-platform that is it runs on Windows, macOS, and Linux.
   - Python is mostly used in Web Development, Data Science and Machine Learning, Automation and Software Development.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   - Go to the official Python website, Download the installer for your operating system,Windows then after installing, Run the downloaded installer. Make sure to check "Add Python to PATH" before clicking "Install Now".
To Verify Installation, Open a terminal or command prompt then type python --version or python3 --version to verify the installation.
To set up a Virtual Environment, Open a terminal or command prompt, Install virtualenv if not already installed: pip install virtualenv. Create a virtual environment: virtualenv myenv (replace myenv with your desired environment name) then finally activate the virtual environment:Windows: myenv\Scripts\activate


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
     
   print("Hello, World!")
print(): A built-in function that outputs text to the console.
"Hello, World!": A string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   - Basic Data Types in python include,
Integer (int): Whole numbers, e.g., 5
Float (float): Decimal numbers, e.g., 3.14
String (str): Text, e.g., "Hello"
Boolean (bool): True or False
List (list): Ordered collection, e.g., [1, 2, 3]
Dictionary (dict): Key-value pairs, e.g., {"key": "value"}

# Creating variables of different data types
x = 10          # Integer
y = 3.14        # Float
name = "Alice"  # String
is_active = True  # Boolean

print(x, y, name, is_active)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - 
# If-else statement
age = 20
if age >= 18:
    print("Adult")
else:
    print("Minor")

# For loop
for i in range(5):
    print(i)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   - Functions are reusable blocks of code that perform a specific task, help to organize code and avoid repetition.
   - def add(a, b):
    return a + b

# Calling the function
result = add(5, 3)
print(result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - Lists are ordered, mutable collections of items while Dictionaries are unordered collections of key-value pairs.
List
numbers = [1, 2, 3, 4, 5]
print(numbers[0])  # Accessing the first element
Dictionary
person = {"name": "Alice", "age": 30}
print(person["name"])  # Accessing the value associated with the key 'name'


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exception Handling helps to manage errors gracefully and continue program execution.
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Execution complete")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   - Modules are files containing Python code while Packages are collections of modules.
   - importing a module
import math

print(math.sqrt(16))



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
       reading from a file
    with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

writing to a file
data = ["Line 1", "Line 2", "Line 3"]
with open('output.txt', 'w') as file:
    for line in data:
        file.write(line + '\n')


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


