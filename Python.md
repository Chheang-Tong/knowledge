![python](/image/Python.jpg)

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

![Example](/image/ImportErrorEx.png)

- `How to Fix:`

```
• Check module and function names carefully
• Install missing modules using pip
• Verify file and folder structure
• Use the correct import statement
```

- `>> Key Error:`

```
A KeyError occurs when you try to access a
dictionary key that does not exist. It typically
happens when you reference a missing key.
```

- `Common Causes`

```
• Accessing a missing key in a dictionary
• Typo or wrong key name
• Using the wrong letter case (keys are case-sensitive)
• Assuming a key exists without checking
```

![Example](/image/KeyErrorEx.png)

- `How to fix`

```
• Check if the key exists using 'in'
• Use .get() to avoid errors
• Verify key names and spelling
• Handle missing keys with try-except
```

> > `>> Zero Division Error:`
