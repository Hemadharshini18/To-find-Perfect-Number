# To-find-Perfect-Number
#include <stdio.h>

int main()
{
	int n;
	scanf("%d",&n);
	int t1=n,i=1,sum=0;

	while(i<n)
	{
	   if(n%i==0)
	    {
	        sum=sum+i;
	    }i++;
	}

	if(n==sum)
	{
		printf("perfect number");
	}
	else
	{
		printf("Not perfect");
	}

return 0;
}

