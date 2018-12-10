Program to find square of a number and display it.

```c
#include <cs50.h>
#include <stdio.h>

int square(int a);

int main(void) {
    int b = get_int("Number:");
    int result = square(b);
    printf("%i\n", result);
}

int square(int a) {
    return a * a;
}
```
