#include<stdio.h>
int main(){
int num1,num2,add,sub,mul,div;

printf("enter a first number:");
scanf("%d",&num1);
printf("enter a second number:");
scanf("%d",&num2);
add=num1+num2;
sub=num1-num2;
mul=num1*num2;
div=num1/num2;
printf("the result of add is:%d\n",add);
printf("the result of sub is:%d\n",sub);
printf("the result of mul is :%d\n",mul);
printf("the result of div is:%d\n",div);
return 0;
}
