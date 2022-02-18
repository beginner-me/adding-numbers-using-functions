# adding-numbers-using-functions
i am using the concept of functions to add numbers
#include<stdio.h>
int sum(int a , int b);//global declaration of function
int main()
{
 int x , y ,res ;
 printf("Enter two numbers : ");
 scanf("%d %d",&x,&y);
  res= sum(x,y);//function calling
  printf("sum of numbers is %d",res);
  	
}
int sum(int a , int b)//function definition
{
	int res;
	res = a + b;
	return res;
}
