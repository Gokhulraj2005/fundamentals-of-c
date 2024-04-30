# EX.NO: 1A
# DATE:
## Write a program to find product of two fraction values.
## AIM:
To Write a program to find product of two fraction values.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b,c;
    scanf("%f%f",&a,&b);
    c=a*b;
    printf("Product of %.2f and %.2f=%.2f",a,b,c);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/2e5776d5-16c0-4081-8a98-917e15e318b1)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 1B
# DATE:
## Write a program in C to read any Month Number in integer and display the number of days for this month.

## AIM:
To Write a program in C to read any Month Number in integer and display the number of days for this month.

## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int month;
    scanf("%d",&month);
    switch(month)
    {
        case 1:
        printf("Month have 31 days.");
        break;
        case 2:
        printf("Month have 28 days.");
        break;
        case 3:
        printf("Month have 31 days.");
        break;
        case 4:
        printf("Month have 30 days.");
        break;
        case 5:
        printf("Month have 31 days.");
        break;
        case 6:
        printf("Month have 30 days.");
        break;
        case 7:
        printf("Month have 31 days.");
        break;
        case 8:
        printf("Month have 31 days.");
        break;
        case 9:
        printf("Month have 30 days.");
        break;
        case 10:
        printf("Month have 31 days.");
        break;
        case 11:
        printf("Month have 30 days.");
        break;
        case 12:
        printf("Month have 31 days.");
        break;
    }
    return 0;
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/b2e8f5ea-737b-4407-9be1-7459cca9fa78)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 1C
# DATE:
## Write a C program to calculate the diameter and circumference of circle.
## AIM:
To Write a C program to calculate the diameter and circumference of circle.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,d,c;
    scanf("%f",&a);
    d=2*a;
    c=2*3.14*a;
    printf("Diameter of circle=%.2f units\n",d);
    printf("Circumference of circle=%.2f units",c);
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/8a993de3-ea82-4b13-a2bd-f9a99315a034)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 1D
# DATE:
## Write a C program to check whether the year is leap year and also which is multiples  of 10 using nested if.
## AIM:
To Write a C program to check whether the year is leap year and also which is multiples  of 10 using nested if.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a%4==0)
    {
        printf("The year is leap year\n");
        if (a%10==0)
        printf("The leap year is also divisible by 10");
        else
        printf("The leap year is Not divisible by 10");
    }
    else
    {
    printf("The year is Not a leap year");
    }
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/07995c26-d595-4bc4-9173-5bace12ab3eb)

## RESULT:
Thus, the above program is executed successfully.
