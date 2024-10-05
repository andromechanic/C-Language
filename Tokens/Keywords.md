
Keywords are reserved words that have a predefined meaning in C programming. They cannot be used as identifiers (names for variables, functions, etc.). Keywords control the structure and flow of the program.

## List of Common Keywords

- **`auto`**: Used to declare automatic variables.
- **`break`**: Exits from a loop or switch statement.
- **`case`**: Defines a branch in a switch statement.
- **`char`**: Declares a character data type.
- **`const`**: Declares a constant value that cannot be modified.
- **`continue`**: Skips the current iteration of a loop and proceeds to the next iteration.
- **`default`**: Specifies the default case in a switch statement.
- **`do`**: Starts a do-while loop.
- **`double`**: Declares a double-precision floating-point data type.
- **`else`**: Defines an alternative branch in an if statement.
- **`enum`**: Defines an enumeration, a user-defined data type consisting of integral constants.
- **`extern`**: Declares a variable or function that is defined in another file.
- **`float`**: Declares a single-precision floating-point data type.
- **`for`**: Starts a for loop.
- **`goto`**: Transfers control to a labeled statement.
- **`if`**: Starts a conditional statement.
- **`int`**: Declares an integer data type.
- **`long`**: Declares a long integer data type.
- **`return`**: Exits from a function and optionally returns a value.
- **`short`**: Declares a short integer data type.
- **`sizeof`**: Returns the size of a data type or variable.
- **`static`**: Declares a variable with static storage duration.
- **`struct`**: Defines a structure, a user-defined data type.
- **`switch`**: Starts a switch statement.
- **`typedef`**: Creates an alias for a data type.
- **`union`**: Defines a union, a user-defined data type that can hold different data types in the same memory location.
- **`unsigned`**: Declares an integer that cannot be negative.
- **`void`**: Specifies that a function does not return a value or indicates an empty data type.
- **`while`**: Starts a while loop.

## Example:

```c
#include <stdio.h>

int main() {
    int a = 5;        // int is a keyword
    const int b = 10; // const is a keyword
    if (a < b) {     // if is a keyword
        printf("a is less than b\n");
    }
    return 0;        // return is a keyword
}
