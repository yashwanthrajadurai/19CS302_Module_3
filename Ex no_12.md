EX NO 3B : C PROGRAM TO CHECK WHETHER THE GIVEN NUMBER IS PRIME OR NOT.

AIM:

To write a program to check whether the given number is prime or not.

ALGORITHM:

1. Start
2. Declare the variable i.
3. Read the value given using scanf.
4. Check whether the given number is prime or not using if-else statement condition.
5. If true,print ("%d is a prime number.",i).
6. If false, print ("%d is not a prime number.",i).
7. End.

PROGRAM:

#include<stdio.h>

int main()

{

int i;

scanf("%d",&i);

if(i%2==1 && i%1==0)

{

printf("%d is a prime number.",i);

}

else

{

printf("%d is not a prime number.",i);

}

return 0;

}

OUTPUT:

![image](https://github.com/user-attachments/assets/78f22a4c-450f-4bd6-995e-f4f6711b1a95)

RESULT:

Thus, the program is executed and verified successfully.
