# Head Recursion:Recursion before Logic
#printing 1 to n if n is odd or printing 2 to n if n is even using recursion
#include<stdio.h>

void printfor(int n)
{if(n<1)
return ;
printfor(n-2);
printf("%d ",n);
}
int main()
{int n;
scanf("%d",&n);
printfor(n);
}
