# firstProject
firstProject For CT 1
#include <stdio.h>
int main() {
char operator;
int num1,num2;
scanf("%c %d %d",&operator,&num1,&num2);
switch(operator){
case '+' :
printf("%d+%d=%d",num1,num2,num1+num2);break;
case '-' :
printf("%d-%d=%d",num1,num2,num1-num2);break;
case '*' :
printf("%d*%d=%d",num1,num2,num1*num2);break;
case '/' :
printf("%d/%d=%d",num1,num2,num1/num2);break;
case '%' :
printf("%d%%%d=%d",num1,num2,num1%num2);break;
default :
printf("Invalid Operator"); }
return 0;}
