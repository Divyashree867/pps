# pps
//Program to print alphabet triangle
#include <stdio.h>
int main()
{
int i, j, k, rows, alphabet;
printf("Enter Triangle Alphabets Pattern Rows = ");
scanf("%d",&rows);
printf("\nThe Triangle Alphabets Pattern\n"); 
for (i = 0 ; i < rows; i++ ) 
{
alphabet = 65;
for (j = rows ; j > i; j-- ) 	
{
printf(" ");
}
for(k = 0; k <= i; k++)
{
printf("%c ", alphabet + k);
}
printf("\n");
}
return 0;
}
