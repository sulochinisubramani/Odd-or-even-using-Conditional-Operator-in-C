# Odd-or-even-using-Conditional-Operator-in-C
#Print the Odd or Even using Conditional Operator, Instead of using if-else statement.(Using Arithmetic Operator) 
#include<stdio.h>
void main(){
    int a;
    printf("Enter the number:");
    scanf("%d",&a);
    (a%2==0) ? printf("Even Number") : printf("Odd Number");
}
