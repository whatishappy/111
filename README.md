#include <stdio.h>
int main()
{
	int count;
	for(int i =1;i<=1000;i++)
		{
			if((i%3==0||i%5==0)&&i%15!=0)
				{
					printf("%d\n",i);
					count++;
				}
		}
		printf("\n there are %d numbers.\n",count);
		return 0;
}
