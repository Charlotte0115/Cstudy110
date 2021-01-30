#include <stdio.h>

int main(void)
{
    int a = 35, b = 14;
    int res = 2;

    a += 23;
    res *= b + 13;

    printf("a = %d, b = %d\n", a, b);
    printf("res = %d\n", res);

    return 0;
}
