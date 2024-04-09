#include <stdio.h>
#define S(X) (X*(X))

int main()
{
int X=5;
for(int i=0;i<3;i++)
{
printf("%d\n",S(X+i));
}
return 0;
}
