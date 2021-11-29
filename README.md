#include<stdio.h>
#include<stdlib.h>
int main()
{
int i,j,k,l,n;
printf("enter the number of rows:");
scanf("%d",&n);
for(i = 0; i <= n; i++)
{
for(k = 0; k <= i; k++)
{
printf("%d",k);
}
printf("\n");
}
return 0;
}
