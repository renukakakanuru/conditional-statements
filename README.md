# conditional-statements
#include<stdio.h>
#include<conio.h>
int main(void)
{
int num;
printf("enter your mark");
scanf("%d",&num);
printf("you entered %d",num);
if(num>=85)
{
printf("you got A grade");
}
else if(num>=70)
{
printf("you got B grade")
}
else if(num>55)
{
printf("you got C grade")
}
else if(num>=40)
{
printf("you got D grade")
}
else if(num<=40)
{
printf( you got F grade)
}
return(0)
}
