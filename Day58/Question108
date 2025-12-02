#include<stdio.h>

int main()
{
    int n;
    printf("Enter the number of elements in the array :");
    scanf("%d",&n);
    if(n<=0)
    {
        printf("Number of array elements cannot be non positive ");
        return 0;
    }
    int nums[n],answer[n];
    for(int i=0;i<n;i++)
    {
        printf("Enter the %d element of the array :",i+1);
        scanf("%d",&nums[i]);
    }
    for(int i=0;i<n;i++)
    {
        answer[i]=1;
        for(int j=0;j<n;j++)
        {
            if(j==i)
            {
                continue;
            }
            answer[i]*=nums[j];
        }
    }
    for(int i=0;i<n;i++)
    {
        printf("%d\t",answer[i]);
    }
   
    return 0;
}
