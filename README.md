# C5
Floyd's triangle 
#include<stdio.h>
int main()
{
 int i,n,j,count=1;
 printf("enter the row of matrix:");
 scanf("%d",&n);
 for(i=1;i<=n;i++){
 for(j=1;j<=i;j++){
 printf ("%d ", count++);
 }
 printf ("\n");
 }
 return 0;
 }
