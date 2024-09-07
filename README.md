# ft_printf - 42 Project

**ft_printf** is focused on recreating the functionality of the standard C `printf` function. 
The project also includes proper error management, ensuring that the function returns `-1` in case of failure, as in the standard `printf`. 

Supports the limited amount of specifiers:

| Specifier | Description                                                        |
|-----------|--------------------------------------------------------------------|
| `%c`      | Prints a single character.                                         |
| `%s`      | Prints a string (as defined by the common C convention).           |
| `%p`      | Prints a `void *` pointer in hexadecimal format.                   |
| `%d`      | Prints a decimal (base 10) number.                                 |
| `%i`      | Prints an integer in base 10.                                      |
| `%u`      | Prints an unsigned decimal (base 10) number.                       |
| `%x`      | Prints a number in hexadecimal (base 16) lowercase format.         |
| `%X`      | Prints a number in hexadecimal (base 16) uppercase format.         |
| `%%`      | Prints a percent sign.                                             |

