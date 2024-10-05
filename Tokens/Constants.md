
Constants are fixed values that do not change during the execution of a program. They are used to store data that should remain unchanged.

## Types of Constants

1. **Integer Constants**: Whole numbers without a decimal point (e.g., `10`, `-5`).
2. **Floating-point Constants**: Numbers with decimal points (e.g., `3.14`, `-0.001`).
3. **Character Constants**: Single characters enclosed in single quotes (e.g., `'A'`, `'z'`).
4. **String Constants**: Sequence of characters enclosed in double quotes (e.g., `"Hello, World!"`).

## Examples:

```c
#include <stdio.h>

int main() {
    const int num = 100;          // Integer constant
    const float pi = 3.14;       // Floating-point constant
    const char letter = 'C';      // Character constant
    const char *greeting = "Hello"; // String constant

    printf("Number: %d\n", num);
    printf("Pi: %.2f\n", pi);
    printf("Letter: %c\n", letter);
    printf("Greeting: %s\n", greeting);
    
    return 0;
}
