# Original Input

Original Input is a Python library that provides a function to get user input and automatically convert it to the appropriate data type. The `original_input()` function can handle a variety of data types, including:

- Numeric (int, float, complex)
- String
- Sequence (list, tuple, range)
- Binary (bytes, bytearray, memoryview)
- Mapping (dict)
- Boolean (bool)
- Set (set, frozenset)
- NoneType

The function uses recursion to handle complex data structures such as lists, tuples, sets, and dictionaries, and tries to convert each element to the appropriate data type. If the input value cannot be converted to any of the recognized data types, it is returned as a string.

## Installation

To install Original Input, use pip:

```bash
pip install original-input
```
### Usage

To use the `original_input()` function, import it from the original_input module and call it with a prompt as input. The function will automatically convert the input value to the appropriate data type and return it. If the input value cannot be converted to any of the recognized data types, it will be returned as a string.

```bash
from original_input import original_input

# Example 1: Getting age as integer
age = original_input("Enter your age: ")
print(f"Your age is {age}, which is of type {type(age)}")

# Example 2: Getting height as float
height = original_input("Enter your height in meters: ")
print(f"Your height is {height}, which is of type {type(height)}")

# Example 3: Getting name as string
name = original_input("Enter your name: ")
print(f"Hello, {name}!")

# Example 4: Getting a complex number
complex_number = original_input("Enter a complex number: ")
print(f"You entered {complex_number}, which is of type {type(complex_number)}")

# Example 5: Getting a list of numbers
numbers = original_input("Enter a list of numbers: ")
print(f"You entered {numbers}, which is of type {type(numbers)}")

# Example 6: Getting employee information as dictionary
employee_info = original_input("Enter employee information: ")
print(f"You entered {employee_info}, which is of type {type(employee_info)}")
```

In each of the examples above, original_input() is called with a prompt to get user input. The returned value is then printed along with its type.
License

`original_input` is released under the MIT License. See [LICENSE](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt) for details.
