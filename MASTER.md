#include<stdio.h>
int main()
{ 
    int a,b; //two integer type variables whose sum is to be performed 
    int sum=0; //the variable for storing the sum of the two integers 
    printf("Enter the first number:"); 
    scanf("%d",&a); 
    printf("Enter the second number:"); 
    scanf("%d",&b);  
    printf("The sum of the two numbers is: %d",a+b); //sum gets printed 
    return 0; 
}
