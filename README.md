#include<stdio.h>
int main()
{
    int a,b,x;
    scanf("%d%d",&a,&b);
    a^=b;
    b ^= a;
    a ^= b;
    printf("a=%d\n b=%d\n",a,b);
    return 0;
}
