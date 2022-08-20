# compound-assignment
This is a general program for compound assignment operator. Its priority is least in all operators.  
#include<stdio.h>
#include<conio.h>
void main()
{
	int a,b;
	printf("Enter one number a:");
	scanf("%d",&a);
	printf("Enter second number b:");
	scanf("%d",&b);
	a*=b;
	printf("Value of a is %d",a);
}


outpu:
Enter one number a:5
Enter second number b:6
Value of a is 30
