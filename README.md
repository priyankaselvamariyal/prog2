#include<stdio.h>
#include<conio.h>
void main()
{
clrscr();
int x;
printf("enter a number:");
scanf("%d",&x);
if(x&1)
{
printf("number is odd");
}
else
{
printf("number is even");
}
getch();
}
