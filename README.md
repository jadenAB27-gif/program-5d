# program-5d
C module 5
EX NO:5-d) Swap two values using pointers. 

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AIM:
To write a c program to swap two numbers using pointers.

ALGORITHM:
1) Get two numbers as input from the user.
2) swap the values of two variables and print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b;
    int *pa=&a,*pb=&b;
    scanf("%d %d",&a,&b);
    printf("m is %d, n is %d\n",*pa,*pb); 
    if(*pa!=*pb)
    {
        *pa=*pa+*pb;
        *pb=*pa-*pb;
        *pa=*pa-*pb;
    }
    printf("m is %d, n is %d",*pa,*pb);
}
```

OUTPUT:


<img width="485" height="263" alt="Screenshot 2025-10-20 201027" src="https://github.com/user-attachments/assets/49414a80-348b-4c97-94e5-a3230da13d76" />


RESULT:

Thus the C program to swap two numbers is successfully executed.







