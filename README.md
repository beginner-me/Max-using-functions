# Max-using-functions
finding minimum and maximum using a function
#include<stdio.h>
int max(int a, int b);
int main()
{
	int a , b, m;
	printf("Enter two numbers :");
	scanf("%d %d", &a,&b);
	
	m = max(a , b);
	printf("Max of the two numbers : %d",m);
}
int max(int a, int b)
{
	int res;
	if(a>b)
	{
		res=a;
	}
	else
	{
		res=b;
	}
	return res;
}
