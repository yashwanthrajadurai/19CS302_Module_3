EX NO 13 : C PROGRAM TO PRINT ONLY ODD ELEMENTS IN 2D ARRAY.

AIM:

To write a program to print only the odd numbers in 2D Array.

ALGORITHM:

1. Start.
2. Define a variables i,j,n,a.
3. Write program to find n x n matrix.
4. Read the value using scanf.
5. Ask the user to make an input
6. Print out the answer.
7. End.

PROGRAM:

#include<stdio.h>

int main()

{

int i,j,n,a[10][10];

scanf("%d",&n);

for(i=0;i<n;i++)

{

for(j=0;j<n;j++)

{

scanf("%d",&a[i][j]);

}

}for(i=0;i<n;i++)

{

for(j=0;j<=n;j++)

{

if(a[i][j]%2==1)

{

printf("a[%d][%d] is %d \n",i,j,a[i][j]);

}

}

printf("\n");

}

return 0;

}

OUTPUT:

![image](https://github.com/user-attachments/assets/0e1fcb96-d585-4eef-8f0a-09b6f237d7ab)

RESULT:

Thus, the program is executed and verified successfully
