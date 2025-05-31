EX NO 11 : C PROGRAM TO CONVERT A GIVEN DECIMAL VALUE TO BINARY USING FUNCTION WITHOUT ARGUMENTS WITH RETURN TYPE.

AIM:

To write a program to convert a given decimal value to binary using function without
arguments with return type.

ALGORITHM:

1. Start.
2. Declare a integer variable
3. Define a function named dectobin.
4. Return the integer.
5. Read the value using scanf.
6. Convert decimal to binary value.
7. Print the dectobin
8. End.

PROGRAM:

 #include<stdio.h>

Int dectobin(int d){

int bin =0,base=1,rem;

while(d>0)

{

rem=d%2;

bin=bin+rem*base;

d=d/2;

base=base*10;

}

printf(" = %d in binary",bin);

return 0;

}

int main()

{

int dec;

scanf("%d",&dec);

printf("%d in decimal",dec);

dectobin(dec);

return 0;

}


OUTPUT:

![Screenshot 2025-05-15 154716](https://github.com/user-attachments/assets/d8b375f7-be81-4052-88bb-9a9c17023d2a)

RESULT:

Thus, the program is executed and verified successfully
