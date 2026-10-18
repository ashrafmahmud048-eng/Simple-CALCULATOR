# Simple-CALCULATOR
#include<stdio.h>

int main(){
int a,b;
scanf("%d %d",&a,&b);
int sum,sub,mult;
float div;
sum=a+b;
sub=a-b;
mult=a*b;
div=(float)a/b;
 printf("Summation is %d\n",sum);
 printf("Subtraction is %d\n",sub);
 printf("Multiplication is %d\n",mult);
 printf("Division is %f\n",div);
 return 0;
}
