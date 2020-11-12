# swapping
swapping 2 variables
#include<stdio.h>
int main(){
	int a,b,temp;
	printf("enter first number ");
	scanf("%d",&a);
	printf("enter the second number= ");
	scanf("%d",&b);
	printf("before swapping first value is %d and second value is %d",a,b);
	temp=a;
	a=b;
	b=temp;
        printf("value after swaping %d and %d",a,b);
	return 0;
	}
