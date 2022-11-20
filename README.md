# 0x11. C - printf
---

## Utilization
* Files compiled with command ```gcc -Wall -Werror -Wextra -pedantic *.c```
* Returns the number of characters in the output success and -1 if not
* Calling : ```_printf("format string", args...)``` 
* ```format string``` can have **flags**, **regular characters** & **specifiers**


---

# Tasks
# |```Mandatory```| 

### [Task 0 | Write a function that produces output according to format ](./functions.c)
  - c : converts input into a character
  - s : converts input into a string

### [Task 1 | Handle the following conversion specifiers:](handle_print.c)
  - d : converts input into a base 10 integer
  - i : converts input into an integer

### [Task 2]()
* Create a man page for your function
---
# | ```Advanced```| 

### [Task 3 | Handle the following conversion specifiers]()
  - b : the unsigned int argument is converted to binary

### [Task 4 | Handle the following conversion specifiers]()
* specifiers:
  - u : converts the input into an unsigned integer
  - o : converts the input into an octal number
  - x : converts the input into a hexadecimal number
  - X : converts the input into a hexadecimal number with capital letters

### [Task | 5]()
* Use a local buffer of 1024 chars in order to call write as little as possible.

### [Task | 6](./print_custom.c)
* Handle the following custom conversion specifier:
  - S : prints the string
  - Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

### [Task | 7](./print_address.c)
* Handle the following conversion specifier:
  - p : int input is converted to a pointer address

### [Task | 8](./get_flag.c)
* Handle the following flag characters for non-custom conversion specifiers:
  - \+ : adds a \+ in front of signed positive numbers and a \- in front of signed negative numbers
  - space : same as \+, but adds a space (is overwritten by \+)
  - \# : adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0X for x or X conversions

### [Task | 9]
* Handle the following length modifiers for non-custom conversion specifiers:
  - l : converts d, i, u, o, x, X conversions in short signed or unsigned ints
  - h : converts d, i, u, o, x, X conversions in long signed or unsigned ints

### [Task | 10]
* Handle the field width for non-custom conversion specifiers.

### [Task | 11]
* Handle the precision for non-custom conversion specifiers.

### [Task | 12]
* Handle the 0 flag character for non-custom conversion specifiers.

### [Task | 13]
* Handle the - flag character for non-custom conversion specifiers.

### [Task | 14)
* Handle the following custom conversion specifier:
  - r : prints the reversed string

### [Task | 15](./print_custom.c)
* Handle the following custom conversion specifier:
  - R : prints the rot13'ed string

### [Task | 16. * ]
* All the above options work well together.

---

