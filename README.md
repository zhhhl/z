#include<stdio.h>
void main()
{
	int x,max,min;
	scanf("%d",&x);
	max=min=x;
	while(x!=0)
	{
		if(x>max)
			max=x;
		if(x<min)
			min=x;
		scanf("%d",&x);
	}
	printf("max=%d,min=%d\n",max,min);
}
