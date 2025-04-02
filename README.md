# Fix My Code Challenge

## Description
This repository contains a collection of broken code snippets that need to be fixed. The project involves debugging existing code rather than creating new implementations from scratch.

## Project Structure
- `0-fizzbuzz.py` - Python implementation of FizzBuzz with a bug (15 prints "Fizz" instead of "FizzBuzz")
- `1-print_square.js` - JavaScript code to print squares with a bug (incorrect square size)
- `2-sort.rb` - Ruby code for sorting arguments with a bug (incorrect sorting algorithm)
- `3-user.py` - Python User class implementation with a bug (issue with password validation)
- `4-delete_dnodeint/` - C implementation of a Double linked list with bugs:
  - `main.c` - Main test file
  - `free_dlistint.c` - Function to free a double linked list
  - `print_dlistint.c` - Function to print a double linked list
  - `add_dnodeint_end.c` - Function to add a node at the end
  - `delete_dnodeint_at_index.c` - Function to delete a node at a specific index (contains bugs)

## Requirements
- All files will be compiled on Ubuntu 20.04 LTS
- All files should end with a new line
- The project is completely optional and intended for practice

## Compilation & Usage

### Python Files
```
./0-fizzbuzz.py 50
./3-user.py
```

### JavaScript Files
```
./1-print_square.js 10
```

### Ruby Files
```
ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
```

### C Files (Double Linked List)
```
gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
./delete_dnodeint
```
