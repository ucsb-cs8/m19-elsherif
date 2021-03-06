---
num: Lecture 16
lecture_date: 2019-07-31
desc: "Final Review"
ready: false
pdfurl:
---

# CS 8 Final Exam Review


- Final Exam: (FILL IN DATE / TIME /LOCATION )
- Exam is cumulative (covers everything from print statements
  to complex data structures)
- Logistics
  - Bring writing utensil (dark led or pen)
  - Bring your student ID
  - No electronic devices
  - Closed and closed notes
- Structure of final is similar to the midterms. Types of questions:
  - Evaluate expressions
  - Evaluate types
  - Given code, what is the output
  - Short answer / definitions
  - Read / write assert statements
  - Complete function definitions / write python statements
  - Fill-in-the-blank
    - complete function definition key terms
    - pass in specific paramaters
    - etc.
  - General Advice
    - Read instructions carefully - pay close attention to
      what is being asked
    - Double-check your work

# Advice on how to prepare

- Lecture notes (important to know topics, examples,
concepts).
  - Type out the code and understand the output
- Understanding labs and being able to implement them
- Reading the textbook for additional details and
  understanding
  - Do the examples to solidify understanding
- Homework exercises
- Prototyping - "I wonder how python behaves when ..."
  - write a simple example
  - Helps with code practice as well as understanding the
    language and edge cases

Overview of topics covered after midterm 2

# File I/O

- Read file (infile = open('example.txt', 'r'))
  - infile.read()
  - infile.read(n)
  - infile.readlines()
  - infile.readline()
  - for a_line in infile
- Write file (outfile = open('example.txt', 'w'))
- Append file (outfile = open('example.txt', 'a'))

# Dictionaries
- key / value pairs
- Creating a dictionary
- Adding to a dictionary
- dictionary methods
  - .pop(key)
  - .update(D2)
  - .get(key)
  - .keys()
  - .values()
  - .items()

# Sets
- Collection of items with no duplicates
- Creating an empty set or a set from a list
- Set operators
  - `in`, `not in`, combine(`|`), intersection(`&`), difference(`-`), unique(`^`)
- Set comparisons
  - `-`, `==`, `!=`, proper subset (`<`), subset (`<=`)
- Set methods
  - `.add`, `.remove` (what happens if item doesn't exist?),
    `.discard`, `.clear`

# Embedded structures

- Dictionary map to dictionary, or dictionary map to set,
  or list of dictionaries, etc.

# Recursion

- Properties of recursion
  - base case
  - recursive calls getting "closer" to base case
- Examples in class and lab
  - print
  - reconstruct lists and strings (reverse a string or list)
  - computing values (factorial, fibonacci, ...)
  - etc.

# Topics covered Previoiusly

See Review on a previous lecture

- Python data types
- Arithmetic
- Python built-in functions
- Comparison operators
- Boolean operators
- Strings
- Lists
- Tuples
- User-defined functions
- Namedtuples
- Testing (`assert` / `pytest`)
- `for` loops
- Nested control structures
- Accumulator Patterns
- Nested (double) for loops
- `while` loops
  - `break`, `continue`, `pass`
- 2D Lists
- String functions and formatting
- Random

