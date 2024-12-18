# **1. Variables and Data Types**

### **Understanding Variables and Data Types in Python**

---

### **1. What is a Variable?**

A **variable** is a named location in memory that stores a value. In Python:

- Variables are **dynamically typed**: You don’t need to declare the type explicitly.
- Assignment is done with `=`.

**Examples:**

```python
python
Copy code
x = 10        # Integer
name = "John" # String
pi = 3.14     # Float
is_valid = True # Boolean

```

---

### **2. Naming Variables**

**Rules**:

1. Must start with a letter or an underscore (`_`).
2. Can contain letters, numbers, and underscores but no spaces.
3. Cannot use Python **reserved keywords** like `if`, `else`, `for`, etc.

**Best Practices**:

- Use descriptive names: `age` instead of `a`.
- Use snake_case for multi-word variables: `user_name`, `max_value`.

---

### **3. Data Types in Python**

| Data Type | Description | Example |
| --- | --- | --- |
| **int** | Integer values | `10`, `-42`, `0` |
| **float** | Decimal numbers | `3.14`, `-0.001` |
| **str** | Text or characters | `"hello"`, `'A'` |
| **bool** | True/False values | `True`, `False` |
| **complex** | Complex numbers | `3+4j` |
| **list** | Ordered, mutable collection | `[1, 2, 3]` |
| **tuple** | Ordered, immutable collection | `(1, 2, 3)` |
| **dict** | Key-value pairs | `{"a": 1, "b": 2}` |
| **set** | Unordered, unique items | `{1, 2, 3}` |
| **NoneType** | Represents a null value | `None` |

---

### **4. Type Checking**

To check a variable's type:

```python
python
Copy code
x = 10
print(type(x))  # <class 'int'>

```

---

### **5. Dynamic Typing in Action**

Python allows you to reassign a variable to a different type:

```python
python
Copy code
x = 10         # x is an integer
x = "Python"   # Now x is a string

```

---

### **Detailed Explanation of Common Data Types**

### **5.1 Numbers**

- **Integers**: Whole numbers (positive, negative, or zero).
- **Floats**: Decimal numbers.
- **Complex Numbers**: Written as `a + bj`, where `a` and `b` are floats.

**Examples:**

```python
python
Copy code
x = 42      # int
y = 3.14    # float
z = 2 + 3j  # complex

```

**Type Conversions**:

```python
python
Copy code
a = float(5)  # Converts int to float
b = int(3.9)  # Converts float to int (truncated)

```

### **5.2 Strings**

- Enclosed in single (`'`), double (`"`), or triple quotes (`'''` or `"""`).
- Strings are immutable (cannot be changed after creation).

**Operations**:

```python
python
Copy code
s = "hello"
print(s[0])       # 'h' (Indexing)
print(s[1:4])     # 'ell' (Slicing)
print(s + " world") # Concatenation
print(s * 3)      # 'hellohellohello'

```

**Common Methods**:

```python
python
Copy code
s = "Python"
print(s.upper())    # 'PYTHON'
print(s.lower())    # 'python'
print(s.replace("Py", "My"))  # 'Mython'

```

### **5.3 Booleans**

- Only two values: `True` and `False`.
- Often used in conditional statements.

**Examples**:

```python
python
Copy code
x = 10
y = 20
print(x > y)  # False
print(x == y) # False

```

### **5.4 Lists**

- Ordered, mutable collections of items.

**Examples**:

```python
python
Copy code
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")   # Adds an item
fruits.remove("banana")   # Removes an item
print(fruits[0])          # 'apple'

```

### **5.5 Dictionaries**

- Stores data as key-value pairs.

**Examples**:

```python
python
Copy code
person = {"name": "John", "age": 30}
print(person["name"])  # 'John'
person["age"] = 31     # Updates value

```

---

### **Advanced Techniques**

### **1. Unpacking Multiple Variables**

Unpack values from a collection into variables:

```python
python
Copy code
x, y, z = 1, 2, 3
a, b = [10, 20]

```

### **2. Swapping Variables**

```python
python
Copy code
x, y = y, x

```

### **3. Augmented Assignment**

Simplify updating a variable:

```python
python
Copy code
x = 10
x += 5  # Equivalent to x = x + 5

```

### **4. Using `type()` and `isinstance()`**

```python
python
Copy code
x = 10
print(isinstance(x, int))  # True

```

### **5. Using F-Strings for Dynamic Strings**

```python
python
Copy code
name = "Alice"
age = 25
print(f"My name is {name} and I'm {age} years old.")

```

### **6. Advanced String Slicing**

```python
python
Copy code
s = "abcdef"
print(s[::-1])  # Reverse string: 'fedcba'

```

### **7. Mutable vs. Immutable Types**

- Immutable: `int`, `float`, `str`, `tuple`.
- Mutable: `list`, `dict`, `set`.

---

### **Tips for Mastery**

1. **Practice Type Conversions**: Convert data types to understand dynamic typing better.
2. **Experiment with Edge Cases**: What happens when you divide by zero or slice beyond bounds?
3. **Debug Type Errors**: Use `type()` often to debug unexpected errors in your code.
4. **Read Documentation**: Learn the full range of methods for each data type (`dir(str)`, `dir(list)`).

---

# **2. Input and Output**

### **Understanding Input and Output in Python**

### **1. Output with `print()`**

The `print()` function is used to display information to the user.

**Basic Syntax**:

```python
python
Copy code
print("Hello, World!")  # Outputs: Hello, World!

```

**Features**:

- Print multiple items separated by a space:
    
    ```python
    python
    Copy code
    print("The sum is:", 5 + 3)  # Outputs: The sum is: 8
    
    ```
    
- Use a custom separator:
    
    ```python
    python
    Copy code
    print("Python", "is", "fun", sep="-")  # Outputs: Python-is-fun
    
    ```
    
- End with a custom character (default is a newline `\n`):
    
    ```python
    python
    Copy code
    print("Hello", end=" ")
    print("World")  # Outputs: Hello World
    
    ```
    

---

### **2. Input with `input()`**

The `input()` function allows the user to provide data during program execution.

**Basic Syntax**:

```python
python
Copy code
name = input("Enter your name: ")
print("Hello, " + name + "!")

```

**How it works**:

- Always returns a string. If you need another type, you must convert it.

**Type Conversion with Input**:

```python
python
Copy code
age = input("Enter your age: ")  # Returns a string
age = int(age)  # Convert to an integer
print("You are", age, "years old.")

```

**Shortcut for Conversion**:

```python
python
Copy code
age = int(input("Enter your age: "))

```

---

### **3. String Formatting with Output**

Python provides several ways to include variables in the output.

**3.1 Using `+` for Concatenation**:

```python
python
Copy code
name = "Alice"
print("Hello, " + name + "!")

```

**3.2 Using `,` for Printing**:

```python
python
Copy code
age = 25
print("You are", age, "years old.")

```

**3.3 Using `str.format()`**:

```python
python
Copy code
name = "Alice"
age = 25
print("My name is {} and I am {} years old.".format(name, age))

```

**3.4 Using F-Strings** (Python 3.6+):

```python
python
Copy code
name = "Alice"
age = 25
print(f"My name is {name} and I am {age} years old.")

```

---

### **4. Advanced Input and Output Techniques**

### **4.1 Reading Multiple Inputs**

If you need multiple inputs on a single line:

```python
python
Copy code
x, y = input("Enter two numbers separated by a space: ").split()
x, y = int(x), int(y)
print(f"The sum is {x + y}")

```

Or in one step:

```python
python
Copy code
x, y = map(int, input("Enter two numbers: ").split())

```

### **4.2 Handling Default Inputs**

Provide a default if the user does not enter anything:

```python
python
Copy code
name = input("Enter your name: ") or "Guest"
print(f"Hello, {name}!")

```

### **4.3 Multi-Line Input**

Use a loop to handle multiple lines of input:

```python
python
Copy code
print("Enter multiple lines (type 'STOP' to end):")
lines = []
while True:
    line = input()
    if line == "STOP":
        break
    lines.append(line)
print("\n".join(lines))

```

### **4.4 Output Formatting with `print()`**

Control spacing and alignment for neat output:

```python
python
Copy code
print(f"{'Name':<10}{'Age':<5}")  # Align left
print(f"{'Alice':<10}{25:<5}")
print(f"{'Bob':<10}{30:<5}")

```

---

### **Tips and Best Practices**

1. **Use F-Strings**: They are concise and readable compared to `.format()` or concatenation.
2. **Validate Input**: Always check if the input is valid (e.g., a number) before using it.
    
    ```python
    python
    Copy code
    while True:
        try:
            num = int(input("Enter a number: "))
            break
        except ValueError:
            print("Invalid input. Please enter a valid number.")
    
    ```
    
3. **Use Descriptive Prompts**: Make it clear what the user should enter.
    
    ```python
    python
    Copy code
    name = input("Please enter your full name: ")
    
    ```
    

---

### **Advanced Techniques**

1. **Reading from a File-like Input Source**:
Use `sys.stdin` for programs that accept input from a file or pipe:
    
    ```python
    python
    Copy code
    import sys
    for line in sys.stdin:
        print(line.strip())
    
    ```
    
2. **Formatted Tables**:
Display data neatly using libraries like `tabulate` or `prettytable`:
    
    ```bash
    bash
    Copy code
    pip install tabulate
    
    ```
    
    ```python
    python
    Copy code
    from tabulate import tabulate
    data = [["Alice", 25], ["Bob", 30], ["Charlie", 22]]
    print(tabulate(data, headers=["Name", "Age"], tablefmt="grid"))
    
    ```
    
3. **Handling Binary Input and Output**:
For advanced file handling:
    
    ```python
    python
    Copy code
    with open("file.bin", "wb") as f:
        f.write(b'Binary data here')
    
    ```
    
4. **Logging Instead of Printing**:
For complex programs, use the `logging` module instead of `print()`:
    
    ```python
    python
    Copy code
    import logging
    logging.basicConfig(level=logging.INFO)
    logging.info("This is an informational message.")
    
    ```
    

---

# **4. Operators**

### **Types of Operators in Python**

Python provides several types of operators:

| **Type** | **Description** |
| --- | --- |
| **Arithmetic** | Perform basic mathematical operations. |
| **Comparison** | Compare two values and return a boolean (`True`/`False`). |
| **Logical** | Combine conditional statements. |
| **Assignment** | Assign or modify values in variables. |
| **Bitwise** | Perform bit-level operations. |
| **Identity** | Check if two variables refer to the same object. |
| **Membership** | Check for membership in sequences (like lists, strings). |

---

### **1. Arithmetic Operators**

Used for mathematical calculations.

| **Operator** | **Description** | **Example** | **Result** |
| --- | --- | --- | --- |
| `+` | Addition | `5 + 3` | `8` |
| `-` | Subtraction | `5 - 3` | `2` |
| `*` | Multiplication | `5 * 3` | `15` |
| `/` | Division | `5 / 2` | `2.5` |
| `//` | Floor Division | `5 // 2` | `2` (drops decimal) |
| `%` | Modulus (remainder) | `5 % 2` | `1` |
| `**` | Exponentiation | `2 ** 3` | `8` |

---

### **2. Comparison Operators**

Used to compare values, returning `True` or `False`.

| **Operator** | **Description** | **Example** | **Result** |
| --- | --- | --- | --- |
| `==` | Equal to | `5 == 5` | `True` |
| `!=` | Not equal to | `5 != 3` | `True` |
| `>` | Greater than | `5 > 3` | `True` |
| `<` | Less than | `5 < 3` | `False` |
| `>=` | Greater than or equal | `5 >= 5` | `True` |
| `<=` | Less than or equal | `5 <= 3` | `False` |

---

### **3. Logical Operators**

Combine multiple conditions.

| **Operator** | **Description** | **Example** | **Result** |
| --- | --- | --- | --- |
| `and` | Returns `True` if all conditions are `True`. | `5 > 3 and 3 > 1` | `True` |
| `or` | Returns `True` if at least one condition is `True`. | `5 > 3 or 3 < 1` | `True` |
| `not` | Negates the condition. | `not(5 > 3)` | `False` |

---

### **4. Assignment Operators**

Used to assign values to variables and modify them.

| **Operator** | **Example** | **Equivalent To** |
| --- | --- | --- |
| `=` | `x = 5` | Assigns `5` to `x`. |
| `+=` | `x += 3` | `x = x + 3` |
| `-=` | `x -= 3` | `x = x - 3` |
| `*=` | `x *= 3` | `x = x * 3` |
| `/=` | `x /= 3` | `x = x / 3` |
| `//=` | `x //= 3` | `x = x // 3` |
| `**=` | `x **= 3` | `x = x ** 3` |
| `%=` | `x %= 3` | `x = x % 3` |

---

### **5. Bitwise Operators**

Used for bit-level operations (binary numbers).

| **Operator** | **Description** | **Example** | **Result** (for `a=5`, `b=3`) |
| --- | --- | --- | --- |
| `&` | AND | `a & b` | `1` (0101 & 0011 = 0001) |
| ` | ` | OR | `a |
| `^` | XOR | `a ^ b` | `6` (0101 ^ 0011 = 0110) |
| `~` | NOT (complement) | `~a` | `-6` |
| `<<` | Left Shift | `a << 1` | `10` (0101 << 1 = 1010) |
| `>>` | Right Shift | `a >> 1` | `2` (0101 >> 1 = 0010) |

---

### **6. Identity Operators**

Used to check if two variables refer to the same object in memory.

| **Operator** | **Description** | **Example** | **Result** |
| --- | --- | --- | --- |
| `is` | Returns `True` if they are the same object. | `x is y` | `True`/`False` |
| `is not` | Returns `True` if they are not the same object. | `x is not y` | `True`/`False` |

---

### **7. Membership Operators**

Used to check membership in collections like strings, lists, etc.

| **Operator** | **Description** | **Example** | **Result** |
| --- | --- | --- | --- |
| `in` | Returns `True` if present. | `'a' in 'apple'` | `True` |
| `not in` | Returns `True` if not present. | `'b' not in 'apple'` | `True` |

---

### **Advanced Techniques**

### **1. Chained Comparisons**

Python allows chaining multiple comparisons in a single line:

```python
python
Copy code
x = 5
print(1 < x < 10)  # True (equivalent to 1 < x and x < 10)

```

### **2. Use Short-Circuiting with Logical Operators**

Logical operators like `and` and `or` stop evaluating as soon as the result is known:

```python
python
Copy code
# Short-circuit: Second condition is not checked if the first is False
x = 5
if x > 0 and x / 0 == 1:  # No error because x > 0 evaluates to False
    print("Won't reach here.")

```

### **3. Bitwise Tricks**

- Swap two numbers without a temporary variable:
    
    ```python
    python
    Copy code
    a = 5
    b = 3
    a = a ^ b
    b = a ^ b
    a = a ^ b
    print(a, b)  # 3, 5
    
    ```
    

### **4. Use Logical Operators for Defaults**

```python
python
Copy code
x = None
y = x or "Default Value"
print(y)  # Outputs: Default Value

```

### **5. Membership with Strings**

Check substrings directly:

```python
python
Copy code
sentence = "Python is awesome"
print("Python" in sentence)  # True

```

---

### **Tips for Mastery**

1. **Understand Precedence**: Learn the order in which operators are evaluated:
    - Parentheses > Exponentiation > Multiplication/Division > Addition/Subtraction > Comparisons > Logical Operators.
    
    ```python
    python
    Copy code
    result = 2 + 3 * 4 ** 2  # Equivalent to 2 + (3 * (4 ** 2))
    print(result)  # 50
    
    ```
    
2. **Practice Boolean Logic**: Build truth tables and test logical combinations.
3. **Debug with Print**: If operations don’t behave as expected, print intermediate results.
4. **Use Built-In Functions**: Python offers functions like `divmod()` for division and remainder:
    
    ```python
    python
    Copy code
    quotient, remainder = divmod(10, 3)
    print(quotient, remainder)  # 3, 1
    
    ```
    

---

# **5. Control Flow**

### **Control Flow Topics**

| **Control Flow Concept** | **Purpose** |
| --- | --- |
| **Conditional Statements** | Execute blocks of code based on conditions. |
| **Loops** | Repeat a block of code multiple times. |
| **Control Keywords** | Alter or control the flow of loops and conditions (`break`, `continue`, `pass`). |

---

## **1. Conditional Statements**

### **1.1 `if` Statement**

Executes a block of code if the condition is `True`.

**Syntax**:

```python
python
Copy code
if condition:
    # Block of code

```

**Example**:

```python
python
Copy code
age = 18
if age >= 18:
    print("You are eligible to vote.")

```

---

### **1.2 `if-else` Statement**

Provides an alternative block of code if the condition is `False`.

**Syntax**:

```python
python
Copy code
if condition:
    # Block of code if condition is True
else:
    # Block of code if condition is False

```

**Example**:

```python
python
Copy code
age = 16
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")

```

---

### **1.3 `if-elif-else` Statement**

Allows checking multiple conditions.

**Syntax**:

```python
python
Copy code
if condition1:
    # Block of code if condition1 is True
elif condition2:
    # Block of code if condition2 is True
else:
    # Block of code if all conditions are False

```

**Example**:

```python
python
Copy code
grade = 85
if grade >= 90:
    print("A")
elif grade >= 80:
    print("B")
elif grade >= 70:
    print("C")
else:
    print("Fail")

```

---

### **1.4 Nested `if` Statements**

Place one `if` inside another for complex conditions.

**Example**:

```python
python
Copy code
num = 5
if num > 0:
    if num % 2 == 0:
        print("Positive Even")
    else:
        print("Positive Odd")

```

---

## **2. Loops**

### **2.1 `while` Loop**

Repeats a block of code as long as a condition is `True`.

**Syntax**:

```python
python
Copy code
while condition:
    # Block of code

```

**Example**:

```python
python
Copy code
i = 1
while i <= 5:
    print(i)
    i += 1

```

---

### **2.2 `for` Loop**

Iterates over a sequence (e.g., list, string, range).

**Syntax**:

```python
python
Copy code
for item in iterable:
    # Block of code

```

**Example**:

```python
python
Copy code
for char in "Python":
    print(char)

```

**Using `range()`**:

```python
python
Copy code
for i in range(1, 6):
    print(i)

```

---

## **3. Control Keywords**

### **3.1 `break`**

Exits the loop prematurely.

**Example**:

```python
python
Copy code
for i in range(1, 10):
    if i == 5:
        break
    print(i)

```

---

### **3.2 `continue`**

Skips the current iteration and moves to the next.

**Example**:

```python
python
Copy code
for i in range(1, 10):
    if i % 2 == 0:
        continue
    print(i)

```

---

### **3.3 `pass`**

A placeholder that does nothing (useful for stubs).

**Example**:

```python
python
Copy code
if True:
    pass  # To be implemented later

```

---

### **Advanced Techniques**

### **1. One-Liner Conditionals**

Write `if` statements in one line:

```python
python
Copy code
age = 18
print("Adult") if age >= 18 else print("Minor")

```

---

### **2. Loop with `else`**

The `else` block in loops executes only if the loop completes without a `break`.

```python
python
Copy code
for i in range(5):
    if i == 3:
        break
else:
    print("Loop completed.")

```

---

### **3. Nested Loops**

Use loops within loops for multi-dimensional data.

```python
python
Copy code
for i in range(1, 4):
    for j in range(1, 4):
        print(f"({i}, {j})", end=" ")
    print()

```

---

### **4. Use `enumerate()` in Loops**

Iterate with an index automatically.

```python
python
Copy code
fruits = ["apple", "banana", "cherry"]
for index, fruit in enumerate(fruits):
    print(f"Index: {index}, Fruit: {fruit}")

```

---

### **5. Loop with `zip()`**

Iterate over two sequences simultaneously.

```python
python
Copy code
names = ["Alice", "Bob"]
scores = [85, 90]
for name, score in zip(names, scores):
    print(f"{name} scored {score}")

```

---

### **6. Avoid Infinite Loops**

Always ensure the condition in a `while` loop eventually becomes `False`.

**Bad Example**:

```python
python
Copy code
while True:  # Infinite loop
    print("Hello")

```

**Fixed**:

```python
python
Copy code
count = 0
while count < 5:
    print("Hello")
    count += 1

```

---

# **6. Functions**

## **What are Functions?**

A function is a block of organized, reusable code that performs a specific task. Functions help make programs easier to write, read, and debug.

---

## **Types of Functions in Python**

1. **Built-in Functions**: Predefined functions like `print()`, `len()`, `input()`, etc.
2. **User-Defined Functions**: Functions you create to perform specific tasks.
3. **Anonymous (Lambda) Functions**: Functions defined without a name for quick, one-time use.

---

## **1. Defining and Calling Functions**

### **Defining a Function**

Functions are defined using the `def` keyword.

**Syntax**:

```python
python
Copy code
def function_name(parameters):
    # Function body
    return value

```

**Example**:

```python
python
Copy code
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))  # Output: Hello, Alice!

```

---

### **Calling a Function**

Once defined, you call a function by its name followed by parentheses.

**Example**:

```python
python
Copy code
result = greet("Bob")
print(result)  # Output: Hello, Bob!

```

---

## **2. Function Parameters and Arguments**

### **2.1 Positional Arguments**

Arguments are matched to parameters by position.

```python
python
Copy code
def add(a, b):
    return a + b

print(add(3, 5))  # Output: 8

```

---

### **2.2 Default Parameters**

Provide a default value if no argument is passed.

```python
python
Copy code
def greet(name="Guest"):
    return f"Hello, {name}!"

print(greet())          # Output: Hello, Guest!
print(greet("Alice"))   # Output: Hello, Alice!

```

---

### **2.3 Keyword Arguments**

Match arguments to parameters by name.

```python
python
Copy code
def display_info(name, age):
    print(f"Name: {name}, Age: {age}")

display_info(age=25, name="Alice")

```

---

### **2.4 Variable-Length Arguments**

- **`args`**: Accepts any number of positional arguments as a tuple.
- **`*kwargs`**: Accepts any number of keyword arguments as a dictionary.

**Example**:

```python
python
Copy code
def summarize(*args, **kwargs):
    print("Positional:", args)
    print("Keyword:", kwargs)

summarize(1, 2, 3, name="Alice", age=25)
# Output:
# Positional: (1, 2, 3)
# Keyword: {'name': 'Alice', 'age': 25}

```

---

## **3. Return Statement**

A function can return a value using the `return` statement.

**Example**:

```python
python
Copy code
def square(num):
    return num ** 2

print(square(4))  # Output: 16

```

### **Returning Multiple Values**

Return multiple values as a tuple.

```python
python
Copy code
def calc(a, b):
    return a + b, a - b, a * b

result = calc(5, 3)
print(result)  # Output: (8, 2, 15)

```

---

## **4. Scope and Lifetime of Variables**

### **Local Scope**

Variables defined inside a function are local and cannot be accessed outside it.

```python
python
Copy code
def my_func():
    x = 10
    print(x)

my_func()
# print(x)  # Error: x is not defined

```

---

### **Global Scope**

Variables defined outside functions can be accessed within functions (but cannot be modified unless declared `global`).

**Example**:

```python
python
Copy code
x = 10  # Global variable

def my_func():
    global x
    x = 20  # Modify global variable
    print(x)

my_func()
print(x)  # Output: 20

```

---

## **5. Anonymous Functions (Lambda Functions)**

Lambda functions are short, inline functions defined using the `lambda` keyword.

**Syntax**:

```python
python
Copy code
lambda parameters: expression

```

**Example**:

```python
python
Copy code
square = lambda x: x ** 2
print(square(5))  # Output: 25

```

**Using `lambda` with `map()` and `filter()`**:

```python
python
Copy code
nums = [1, 2, 3, 4]
squared = map(lambda x: x ** 2, nums)
print(list(squared))  # Output: [1, 4, 9, 16]

even = filter(lambda x: x % 2 == 0, nums)
print(list(even))  # Output: [2, 4]

```

---

## **6. Recursive Functions**

A function that calls itself to solve a smaller instance of a problem.

**Example**:

```python
python
Copy code
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))  # Output: 120

```

---

## **Advanced Techniques**

### **1. Function Decorators**

A decorator modifies the behavior of a function.

**Example**:

```python
python
Copy code
def decorator(func):
    def wrapper():
        print("Before function call")
        func()
        print("After function call")
    return wrapper

@decorator
def say_hello():
    print("Hello!")

say_hello()

```

---

### **2. Function Annotations**

Annotations provide metadata about function arguments and return types.

**Example**:

```python
python
Copy code
def add(a: int, b: int) -> int:
    return a + b

print(add(3, 5))  # Output: 8

```

---

### **3. Partial Functions (from `functools`)**

Create a new function by fixing some parameters of an existing function.

**Example**:

```python
python
Copy code
from functools import partial

def power(base, exp):
    return base ** exp

square = partial(power, exp=2)
print(square(5))  # Output: 25

```

---

### **Tips for Mastery**

1. **Write Reusable Functions**: Avoid hardcoding values inside functions.
2. **Use Docstrings**: Document your functions with `"""description"""` for clarity.
3. **Keep Functions Small**: Each function should do one thing well.
4. **Avoid Global Variables**: They make debugging harder; pass parameters instead.
5. **Test Edge Cases**: Ensure functions handle invalid inputs gracefully.
6. **Leverage Built-in Functions**: Python’s standard library often provides optimized alternatives.

---

# **7. Data Structures**

Data structures are foundational to programming, as they help organize and manage data efficiently. Python provides several built-in data structures, each suited to specific use cases. Let's dive into **data structures** in Python in full detail.

---

## **Types of Data Structures in Python**

1. **Lists**
2. **Tuples**
3. **Sets**
4. **Dictionaries**
5. **Strings** (sometimes considered a data structure)
6. **Custom Data Structures** (e.g., classes, linked lists, etc.)

---

## **1. Lists**

A list is a mutable, ordered collection that can contain elements of any data type.

### **Key Characteristics**

- Ordered (maintains insertion order).
- Mutable (modifiable after creation).
- Allows duplicates.

**Example**:

```python
python
Copy code
my_list = [1, 2, 3, "Python", True]

```

### **Basic Operations**

| **Operation** | **Example** | **Output** |
| --- | --- | --- |
| Access elements | `my_list[0]` | `1` |
| Slicing | `my_list[1:3]` | `[2, 3]` |
| Append | `my_list.append(4)` | `[1, 2, 3, ..., 4]` |
| Insert | `my_list.insert(2, "new")` | `[1, 2, 'new', ...]` |
| Remove | `my_list.remove(2)` | `[1, 3, ...]` |
| Pop | `my_list.pop()` | `[1, 2, 3, ...]` |
| Length | `len(my_list)` | `5` |

**Advanced Techniques**:

- List comprehensions for concise filtering or transformation:
    
    ```python
    python
    Copy code
    squares = [x**2 for x in range(5)]
    print(squares)  # Output: [0, 1, 4, 9, 16]
    
    ```
    

---

## **2. Tuples**

A tuple is an immutable, ordered collection of elements.

### **Key Characteristics**

- Ordered (maintains insertion order).
- Immutable (cannot be modified after creation).
- Allows duplicates.

**Example**:

```python
python
Copy code
my_tuple = (1, 2, 3, "Python", True)

```

### **Basic Operations**

| **Operation** | **Example** | **Output** |
| --- | --- | --- |
| Access elements | `my_tuple[0]` | `1` |
| Slicing | `my_tuple[1:3]` | `(2, 3)` |
| Concatenation | `my_tuple + (4, 5)` | `(1, 2, ..., 4, 5)` |
| Length | `len(my_tuple)` | `5` |

**Advanced Techniques**:

- Use tuples as keys in dictionaries (because they are hashable):
    
    ```python
    python
    Copy code
    coords = {(0, 0): "Origin", (1, 1): "Point A"}
    
    ```
    

---

## **3. Sets**

A set is an unordered collection of unique elements.

### **Key Characteristics**

- Unordered (no indexing).
- Mutable (modifiable after creation).
- No duplicates.

**Example**:

```python
python
Copy code
my_set = {1, 2, 3, 3}  # Duplicate 3 is ignored

```

### **Basic Operations**

| **Operation** | **Example** | **Output** |
| --- | --- | --- |
| Add elements | `my_set.add(4)` | `{1, 2, 3, 4}` |
| Remove elements | `my_set.remove(2)` | `{1, 3, 4}` |
| Union | `set1 | set2` |
| Intersection | `set1 & set2` | Common elements |
| Difference | `set1 - set2` | Unique to `set1` |

**Advanced Techniques**:

- Use sets to remove duplicates from a list:
    
    ```python
    python
    Copy code
    unique_items = list(set([1, 2, 2, 3]))
    print(unique_items)  # Output: [1, 2, 3]
    
    ```
    

---

## **4. Dictionaries**

A dictionary is a mutable, unordered collection of key-value pairs.

### **Key Characteristics**

- Unordered (in Python 3.7+, maintains insertion order).
- Mutable.
- Keys must be unique and hashable.

**Example**:

```python
python
Copy code
my_dict = {"name": "Alice", "age": 25, "skills": ["Python", "C++"]}

```

### **Basic Operations**

| **Operation** | **Example** | **Output** |
| --- | --- | --- |
| Access values | `my_dict["name"]` | `"Alice"` |
| Add/update key | `my_dict["location"] = "NY"` | Adds/updates `"location"` |
| Remove key | `del my_dict["age"]` | Removes `"age"` |
| Keys, values, items | `my_dict.keys()` | Keys of dictionary |

**Advanced Techniques**:

- Dictionary comprehensions:
    
    ```python
    python
    Copy code
    squares = {x: x**2 for x in range(5)}
    print(squares)  # Output: {0: 0, 1: 1, ..., 4: 16}
    
    ```
    

---

## **5. Strings**

Strings are immutable sequences of characters.

### **Key Characteristics**

- Ordered.
- Immutable.

**Example**:

```python
python
Copy code
my_string = "Hello, Python!"

```

### **Basic Operations**

| **Operation** | **Example** | **Output** |
| --- | --- | --- |
| Access characters | `my_string[0]` | `"H"` |
| Slicing | `my_string[0:5]` | `"Hello"` |
| Split | `my_string.split(",")` | `["Hello", " Python!"]` |
| Join | `" ".join(["Hello", "World"])` | `"Hello World"` |

**Advanced Techniques**:

- Reverse a string:
    
    ```python
    python
    Copy code
    reversed_string = my_string[::-1]
    print(reversed_string)  # Output: "!nohtyP ,olleH"
    
    ```
    

---

## **Advanced Tips and Techniques**

### **1. Nested Data Structures**

Combine data structures for complex data organization.

```python
python
Copy code
nested = {
    "students": [
        {"name": "Alice", "age": 20},
        {"name": "Bob", "age": 22},
    ]
}
print(nested["students"][0]["name"])  # Output: Alice

```

---

### **2. Choosing the Right Data Structure**

- Use **lists** for ordered collections where duplicates are allowed.
- Use **sets** for unique elements.
- Use **dictionaries** for key-value mappings.
- Use **tuples** for immutable data.

---

### **3. Iterating Efficiently**

- Use `enumerate()` to iterate with an index:
    
    ```python
    python
    Copy code
    for idx, value in enumerate(["a", "b", "c"]):
        print(idx, value)
    
    ```
    
- Use `zip()` to iterate over multiple sequences:
    
    ```python
    python
    Copy code
    for key, value in zip(["name", "age"], ["Alice", 25]):
        print(f"{key}: {value}")
    
    ```
    

---

# **8. String Manipulation**

---

# **9. File Handling**

---

# **10. Error Handling**

---

# **11. Modules and Libraries**

---

# **12. List Comprehensions**

---

# **13. Object-Oriented Programming (OOP) Basics**

---

# **14. Working with External Libraries**
