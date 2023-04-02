#include <stdio.h>
#include <stdlib.h>

int main()
{
	int n,i,j;
	scanf("%d",&n);
	int *arr = (int*)malloc(sizeof(int) * n);
	int tmp;
	for(i=0;i<n;i++)
	{
		scanf("%d",&arr[i]);
	}
	
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			if(arr[i]  < arr[j])
			{
				tmp = arr[i];
				arr[i] = arr[j];
				arr[j] = tmp;	
			}
		}
		
	}
	
	int result = arr[n-1] - arr[0];
	printf("%d",result);
}
