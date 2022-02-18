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


\*#include<stdio.h>
int min(int a , int b);
int main()
{
	int a,b,m;
	printf("Enter numbers to compare : ");
	scanf("%d %d",&a,&b);
	m=min(a,b);
	printf("Minimum of numbers = %d",m);

}
int min(int a,int b)
{
	int res;
	if(a>b)
	 res=b;
	else
	 res=a;
	return res;  
	
}*\
