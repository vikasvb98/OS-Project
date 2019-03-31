#include<stdio.h>
#include <math.h>
int main()
{
             int queue[5000],n,head=125,i,j,k,seek=0,diff;
             float avg;
             printf("Enter the size of Remaining cyinders\t");
             scanf("%d",&n);
             printf("Enter the cylinder loctions\t");
             for(i=1;i<=n;i++)
             {
                          scanf("%d",&queue[i]);
             }
             queue[0]=head;
             printf("\n");
             for(j=0;j<=n-1;j++)
             {
                          diff=abs(queue[j+1]-queue[j]);
                          seek+=diff;
             }
             printf("\nTotal head movement is %d\t",seek);
}
