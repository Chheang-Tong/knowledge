- [](/image/Python.jpg)
- `What is Error Handling in Python?`

```text
Error handling in Python is a way to manage errors
that occur while a program is running so that the
program does not crash and can continue executing
smoothly using try, except, else, and finally blocks.
```

- `Why Error Handling Matters?`

```text
• Prevents your program from crashing
• Handles unexpected user input safely
• Makes your code more reliable
• Improves user experience
• Helps you debug and maintain code easily
• Required for real-world applications
```

- `>> Import Error:`

```text
An ImportError happens when Python cannot find
or load a module, or when a requested item does
not exist within that module.
```

- `Common Causes:`

```
• Module is not installed
• Wrong module or package name
• Trying to import something that doesn't exist
• Incorrect project or file structure
```

- `Example:`

```
from math import sqr ---ImportError: cannot
                     ---import name 'sqr'
result = sqr (9)
print(result)
```

- `How to Fix:`

```
• Check module and function names carefully
• Install missing modules using pip
• Verify file and folder structure
• Use the correct import statement
```
