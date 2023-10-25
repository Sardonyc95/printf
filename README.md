# printf Team Project by Victoria and David
                           Group project on C - Printf

## Overview
### Printf function brief - What to know to create your own Printf function

This is one of many major projects that you will undertake in this program and the essence of this project is for you to put into practice all the concepts that you have been introduced to so far and see how they all work together in a real world use case.
The printf function is a very important and versatile function in the C programming language and being about to create your custom version of it will go a long way to enhance your understanding of the language.
The first secret to being able to complete this project successfully is to first get a solid understanding of the printf function itself, how it works and all the different ways in which it can be used.
This concept page will therefore give you a detailed explanation of how the printf function works and that will go a long way to help you understand what it takes to create a custom version of it.

### Concepts
For this project, we expect you to look at these concepts:
- Group Projects
- Pair Programming - How To
- Flowcharts
- Technical Writing
- Printf function brief - What to know to create your own Printf function
- All about Team Projects + Pairings + FAQ (A must read)

#### Here is the outline for the concept page covered:
1. Introduction to printf
- Brief overview of printf and its role in C programming.
- The format string: How printf uses format specifiers to control output.
2. Argument Handling
- How printf handles variable numbers of arguments.
- Variadic functions in C.
- Parsing the format string to find placeholders.
3. Processing Format Specifiers
- Understanding format specifiers like %d, %s, %c, etc.
- How printf matches format specifiers to arguments.
- Handling flags, field width, precision, and length modifiers.
4. Converting and Formatting
- The role of type conversion in printf.
- How to format data for output based on the format specifier.
- Handling different data types: integers, characters, strings, floats, etc.
5. Output Generation
- How printf generates the final formatted output.
- Building the output string based on the format and arguments.
- Buffering and writing to the standard output.
6. Error Handling
- Dealing with format string errors.
- Handling argument mismatches.
- Returning error codes or handling exceptions.
7. Modifiers and Special Cases
- Handling special format specifiers like %% and %n.
- Modifiers like * for dynamic field width and precision.
8. Memory Management
- If you want your custom printf to allocate memory dynamically, understanding memory management is crucial.
9. Testing and Debugging
- Strategies for testing your custom printf function.
- Debugging common issues.
10. Optimization and Efficiency
- Tips for optimizing your custom printf for performance.

For more info on the concept page outline listed above, check the link below.
Printf function brief - What to know to create your own Printf function: https://intranet.alxswe.com/concepts/100034

                                    TASK QUESTIONS
### Task 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life

Write a function that produces output according to a format.

- Prototype: int _printf(const char *format, ...);
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- write output to stdout, the standard output stream
- format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
     c
     s
     %
- You don’t have to reproduce the buffer handling of the C library printf function
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers

### Task 1. Education is when you read the fine print. Experience is what you get if you don't

Handle the following conversion specifiers:
- d
- i
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers

### Task 2. With a face like mine, I do better in print

Handle the following custom conversion specifiers:
- b: the unsigned int argument is converted to binary

### Task 3. What one has not experienced, one will never understand in print

Handle the following conversion specifiers:
- u
- o
- x
- X
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers

### Task 4. Nothing in fine print is ever good news

Use a local buffer of 1024 chars in order to call write as little as possible.

### Task 5. My weakness is wearing too much leopard print

Handle the following custom conversion specifier:
- S : prints the string.
- Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

### Task 6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print

Handle the following conversion specifier: p.
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers

### Task 7. The big print gives and the small print takes away

Handle the following flag characters for non-custom conversion specifiers:
- +
- space
- #

### Task 8. Sarcasm is lost in print

Handle the following length modifiers for non-custom conversion specifiers:
- l
- h
Conversion specifiers to handle: d, i, u, o, x, X

### Task 9. Print some money and give it to us for the rain forests

Handle the field width for non-custom conversion specifiers.

### Task 10. The negative is the equivalent of the composer's score, and the print the performance

Handle the precision for non-custom conversion specifiers.

### Task 11. It's depressing when you're still around and your albums are out of print

Handle the 0 flag character for non-custom conversion specifiers.

### Task 12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection

Handle the - flag character for non-custom conversion specifiers.

### Task 13. Print is the sharpest and the strongest weapon of our party

Handle the following custom conversion specifier:
- r : prints the reversed string

### Task 14. The flood of print has turned reading into a process of gulping rather than savoring

Handle the following custom conversion specifier:
- R: prints the rot13'ed string

### Task 15. *

All the above options work well together. [ gcc -Wall -Wextra -Werror -pedantic -std=gnu89 -Wno-format *.c ]
