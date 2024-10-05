

Strings in C are arrays of characters that are terminated by a null character (`\0`). They are used to store and manipulate text.

## Declaring Strings

Strings can be declared as arrays of characters.

### Example:

```c
#include <stdio.h>

int main() {
    char name[20] = "John Doe"; // Declaring a string

    printf("Name: %s\n", name); // Using %s to print the string
    
    return 0;
}
```

```c
#include <stdio.h>
#include <string.h>

int main() {
    char str1[20] = "Hello, ";
    char str2[20] = "World!";
    
    strcat(str1, str2); // Concatenates str2 to str1
    
    printf("Concatenated String: %s\n", str1);
    
    return 0;
}

