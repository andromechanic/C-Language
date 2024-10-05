

Identifiers are names given to various program elements such as variables, functions, arrays, etc. They are used to identify these elements during the program execution.

## Rules for Identifiers

1. **Must Start with a Letter or Underscore**: An identifier must start with an alphabet (`a-z`, `A-Z`) or an underscore (`_`).
2. **Subsequent Characters**: After the first character, identifiers can contain letters, digits (`0-9`), and underscores.
3. **Case Sensitive**: Identifiers are case sensitive; `Variable` and `variable` are different identifiers.
4. **No Length Limit**: Although the C standard does not specify a limit, it's best to keep identifiers reasonably short for readability.
5. **Cannot be a Keyword**: Identifiers cannot be the same as C keywords.

## Examples:

```c
#include <stdio.h>

int main() {
    int age;           // 'age' is an identifier
    float height;     // 'height' is an identifier
    char name[20];    // 'name' is an identifier
    age = 25;         // Assigning value to 'age'
    height = 5.9;     // Assigning value to 'height'
    
    printf("Age: %d, Height: %.1f\n", age, height);
    
    return 0;
}
