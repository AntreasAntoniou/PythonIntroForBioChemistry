## Tutorial 2: Python Basics and Your First Biochemistry Program

Welcome back! 🥳 Now that you're familiar with Google Colab and have written your first Python program, let's dive into the basics of Python.

### Objective 🎯

Understand Python basics, including variables, data types, and operations. Use this knowledge to write a program that calculates the molar mass of a given compound.

#### Step 1: Python Basics

Python has several basic types of data. The most common are:

**Strings**: Strings are sequences of characters, like "Hello, World!". You define strings by surrounding the content with quotes (" " or ' ').
**Integers**: Integers are whole numbers, like 5, 42, or -3.
**Floats**: Floats are decimal numbers, like 3.14, 0.009, or -7.6.
**Booleans**: Booleans represent the truth values, which are either True or False.
In Python, we store data in variables. Here's how to create a variable:

```python
# This is a comment - any text following the # symbol is not executed
# Let's create some variables!
greeting = "Hello, World!"  # a string
num_protons = 6  # an integer
pi_value = 3.14  # a float
is_python_fun = True  # a boolean
```
Now, try creating your own variables in a new cell in your Google Colab notebook!

#### Step 2: Your First Biochemistry Program 🧪

One common task in biochemistry is calculating the molar mass of a compound. Let's write a program to calculate the molar mass of water (H2O).

First, we need to define the molar mass of each element:

```python
H_mass = 1.007  # hydrogen
O_mass = 15.999  # oxygen
```
Next, let's calculate the molar mass of water. Water has 2 hydrogen atoms and 1 oxygen atom, so its molar mass is 2*H_mass + 1*O_mass:

```python
water_mass = 2*H_mass + 1*O_mass
print("The molar mass of water is", water_mass, "g/mol")
```
Run the code. You should see the molar mass of water printed below the cell.

Congratulations, you've written your first biochemistry Python program! 🎉

### What's next?

Fantastic job on completing Tutorial 2! You've learned some Python basics and wrote a biochemistry program. In the next tutorial, we'll explore more complex data types and operations, and use them to solve more complex biochemistry problems. See you there!



