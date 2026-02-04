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

> > `>> Import Error:`

```text
An ImportError happens when Python cannot find
or load a module, or when a requested item does
not exist within that module.
```

- `Common Causes`

```
• Module is not installed
• Wrong module or package name
• Trying to import something that doesn't exist
• Incorrect project or file structure
```

![Example](/image/ImportErrorEx.png)

- `How to Fix`

```
• Check module and function names carefully
• Install missing modules using pip
• Verify file and folder structure
• Use the correct import statement
```

> > `>> Key Error:`

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

```
A ZeroDivisionError occurs when you attempt to
divide a number by zero, which is not permitted in
Python.
```

- `Common Causes`

```
• Dividing by O
• Using a variable whose value becomes O
• Incorrect calculations
• Incorrect user input
```

![Example](/image/DivisionErrorEx.png)

- `How to fix`

```
• Check if the value is zero before dividing
• Validate user input
• Use try-except to handle division safely
```

> > `>> Index Error:`

```
An IndexError occurs when you try to access an
index that does not exist in a list, tuple, or string.
This happens when the index is out of range.
```

- `Common Causes`

```
• Accessing an index outside the range
• Using a negative index incorrectly
• Looping beyond the length of a list
• Assuming an element exists when it doesn't
```

![Example](/image/IndexErrorEx.png)

- `How to fix`

```
• Check the length using len()
• Make sure the index exists before accessing
• Use proper loop conditions
• Handle cases with try-except if needed
```

> > `>> Value Error:`

```
A ValueError occurs when Python receives a correct
data type but the value itself is invalid or
inappropriate.
```

- `Common`

```
• Converting invalid values (e.g. int("abc"))
• Passing an invalid value to a function
• Incorrect input format
• Values outside the expected range
```

![Example](/image/ValueErrorEx.png)

- `How to fix`

```
• Ensure the value matches the expected format
• Validate user input before conversion
• Use try-except to handle invalid values
• Print and check values while debugging
```

> > `Attribute Error:`

```
An AttributeError occurs when you attempt to
access an attribute or method that an object does
not define.
```

- `Common`

```
• Calling a method that doesn't exist for that data type
• Misspelling method or attribute names
• Using the wrong object type
• Assuming all objects have the same methods
```

![Example](/image/AttributeErrorEx.png)

- `How to fix`

```
• Check which methods belong to the object
• Use type() to confirm the object type
• Fix spelling mistakes
• Use the correct data type for the operation
```
>> `>> Logical Error:`
```
A Logical Error occurs when your code runs without
errors but produces incorrect output.
```
- `Common`
```
• Logical mistakes in code
• Infinite loops or recursion issues
• Resource limitations (memory, time)
• Incorrect use of built-in functions
```
![Example](/image/LogicalErrorEx.png)
- `How to fix`
```
• Recheck logic and conditions
• Use print statements to debug values
• Break the code into smaller parts
• Test with multiple inputs
```