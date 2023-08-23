#include <stdio.h>
int main()
{
    int x=10,y=20,z=30;
    if(x<y && x<z)
    {
        printf("%d is samllest", x);
    }
    else if(y<x && y<z)
    {
        printf("%d is samllest",y);
    }
    else if(z<x && z<y)
    {
        printf("%d is samllest",z);
    }
    else
    {
        printf("invaild");

    }
    return 0;
}
