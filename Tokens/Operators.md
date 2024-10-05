
Operators in C are special symbols that perform operations on variables and values. They are categorized into several types based on their functionality.

## 1. Relational Operators

Relational operators are used to compare two values.

| Operator | Description                |
|----------|----------------------------|
| `==`     | Equal to                   |
| `!=`     | Not equal to               |
| `>`      | Greater than               |
| `<`      | Less than                  |
| `>=`     | Greater than or equal to   |
| `<=`     | Less than or equal to      |

### Example:

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20;
    printf("Is a equal to b? %d\n", a == b);
    printf("Is a not equal to b? %d\n", a != b);
    return 0;
}
```

## 2. Logical Operators

Logical operators are used to combine multiple conditions.

| Operator | Description  |
|----------|--------------|
| `&&`     | Logical AND  |
| `||`     | Logical OR   |
| `!`      | Logical NOT  |

### Example:

```c
#include <stdio.h>

int main() {
    int a = 5, b = 10;
    if (a < b && b > 0) {
        printf("Both conditions are true.\n");
    }
    return 0;
}
```

## 3. Bitwise Operators

Bitwise operators operate on bits and perform bit-level operations.

| Operator | Description       |
|----------|-------------------|
| `&`      | Bitwise AND       |
| `|`      | Bitwise OR        |
| `^`      | Bitwise XOR       |
| `~`      | Bitwise NOT       |
| `<<`     | Left shift        |
| `>>`     | Right shift       |

### Example:

```c
#include <stdio.h>

int main() {
    int a = 5; // 0101 in binary
    int b = 3; // 0011 in binary
    printf("Bitwise AND: %d\n", a & b); // 0001
    printf("Bitwise OR: %d\n", a | b); // 0111
    return 0;
}
```

## 4. Assignment Operators

Assignment operators are used to assign values to variables.

| Operator | Description             |
|----------|-------------------------|
| `=`      | Simple assignment       |
| `+=`     | Add and assign          |
| `-=`     | Subtract and assign     |
| `*=`     | Multiply and assign     |
| `/=`     | Divide and assign       |

### Example:

```c
#include <stdio.h>

int main() {
    int a = 5;
    a += 10; // a = a + 10
    printf("Value of a: %d\n", a);
    return 0;
}
```

## 5. Ternary Operator

The ternary operator is a shorthand for the if-else statement.

### Syntax: 
`condition ? expression1 : expression2`

### Example:

```c
#include <stdio.h>

int main() {
    int a = 5;
    int result = (a > 0) ? a : -a; // If a is positive, result is a; otherwise, result is -a
    printf("Result: %d\n", result);
    return 0;
}
```

## 6. Comma Operator

The comma operator is used to separate expressions.

### Syntax: 
`expression1, expression2`

### Example:

```c
#include <stdio.h>

int main() {
    int a = 1, b = 2;
    int result = (a++, b++); // Increments a and b
    printf("Result: %d, %d\n", a, b); // a: 2, b: 3
    return 0;
}
```

## 7. Sizeof Operator

The sizeof operator returns the size of a data type or variable.

### Example:

```c
#include <stdio.h>

int main() {
    printf("Size of int: %zu bytes\n", sizeof(int));
    return 0;
}
```
