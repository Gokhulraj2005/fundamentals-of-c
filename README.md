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

# EX.NO: 2A
# DATE:
## Print square number pattern of one and zero with one at odd row and zero at even row using loop in C programming

## AIM:
To write and print square number pattern of one and zero with one at odd row and zero at even row using loop in C programming
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int row,col;
    scanf("%d%d",&row,&col);
    for(int i=1;i<=row;i++)
    {
    for(int j=1;j<=col;j++)
    {
        if(i%2!=0)
        {
        printf("0");
        }
        else
        {
        printf("1");
        }
    }
    printf("\n");
    }
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/03d7cb3c-9fa7-43e4-b702-7cb551483185)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 2B
# DATE:
## Write a C program to print rhombus  pattern
## AIM:
To Write a C program to print rhombus  pattern
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int i,j,row;
    scanf("%d",&row);
    for(i=1;i<=row;i++)
    {
        for(j=1;j<=row-i;j++)
        {
            printf(" ");
        }
        for (j=1;j<=row;j++)
        {
            printf("*");
        }
        printf("\n");
    }
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/3cf4c87e-3bd3-46f3-af0b-1364a5b53ead)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 2C
# DATE:
## Write a C program to generate Fibonacci series for given number using function without return type & without arguments.
## AIM:
To Write a C program to generate Fibonacci series for given number using function without return type & without arguments.
## PROGRAM:
```
#include <stdio.h>
void stat()
{
    int n,f=0,s=1,nxt,i;
    scanf("%d",&n);
    for (i=0;i<n;i++)
    {
        printf("%d ",f);
        nxt=f+s;
        f=s;
        s=nxt;
        
    }
}
int main()
{
    stat();
    
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/19337dd2-bf2b-408f-b8ae-03657ff9380a)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 2D
# DATE:
## Write a C program to check the input entered by the user is palindrome or not using while loop.
## AIM:
To Write a C program to check the input entered by the user is palindrome or not using while loop.
## PROGRAM:
```
#include<stdio.h>
#include<string.h>
int main()
{
    char str[100];
    int l=0,h=0,is_palindrome=1;
    scanf("%s",str);
    h=strlen(str)-1;
    while(h>l)
    {
        if(str[l++]!=str[h--])
    {
        is_palindrome=0;
    }
        
    }
    if (is_palindrome)
    {
     printf("Palindrome Number");
     
    }
    else
    {
        printf("Not a Palindrome Number");
    }
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/9de262f6-6206-407e-a60d-86cc73ddf493)


## RESULT:
Thus, the above program is executed successfully.



# EX.NO: 3A
# DATE:
## write a program to calculate age using function with return type with arguments.

## AIM:
To write a program to calculate age using function with return type with arguments.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int d1,m1,y1;
    int d2,m2,y2;
    scanf("%d%d%d",&d1,&m1,&y1);
    scanf("%d%d%d",&d2,&m2,&y2);
    int re1;
    int re2;
    if(d1<d2&&m1>m2&&y1>y2)
    {
        re1=y1-y2;
        printf("Present Age is : %d",re1);
        
    }

    else
    {
    re2=y1-y2-1;
    printf("Present Age is : %d",re2);
}
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/b1a77cb5-9771-4fd4-8f8a-bbed36b68ee3)


## RESULT:
Thus, the above program is executed successfully.



# EX.NO: 3B
# DATE:
## Create a C program  to check whether the given number is prime or not.


## AIM:
To Create a C program  to check whether the given number is prime or not.

## PROGRAM:
```
#include <stdio.h>
int main() {
  int n, i, flag = 0;
 
  scanf("%d", &n);

  for (i = 2; i <= n / 2; ++i) {
    
    if (n % i == 0) {
      flag = 1;
      break;
    }
  }

  if (n == 1) {
    printf("1 is neither prime nor composite.");
  } 
  else {
    if (flag == 0)
      printf("%d is a prime number.", n);
    else
      printf("%d is not a prime number.", n);
  }

  return 0;
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/ff9e3f1e-9b98-4c35-af67-0cd289925573)


## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 3C
# DATE:
## Write  a C program to read the elements of the n x n matrix and print the last element of the matrix

## AIM:
To Write  a C program to read the elements of the n x n matrix and print the last element of the matrix
## PROGRAM:
```
#include <stdio.h>

int main()
{
    int i,j,n;
    
    scanf("%d",&n);
    int  a[n][n];
    for(i=0;i<n;i++)
    {
       for(j=0;j<n;j++)
       {
        scanf("%d",&a[i][j]);
}
}
        printf("a[%d][%d] is %d ",n-1, n-1,a[n-1][n-1]);

    return 0;
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/17fdf606-c460-40cf-b36a-312c44d95964)

## RESULT:
Thus, the above program is executed successfully.



# EX.NO: 3D
# DATE:
## Write a C Program to search a element in an  1 - D array.

## AIM:
To Write a C Program to search a element in an  1 - D array.
## PROGRAM:
```

#include <stdio.h>
int main()
{
    int i,n, key;
    scanf("%d", &n);
   int a[100];
    for(i=0; i<n; i++)
    {
        scanf("%d",&a[i]);
    }

    scanf("%d", &key);
     
    for(i=0; i<n; i++)
    {
        if(a[i]==key)
        {
			printf("element found" );
            return 0;		 
        }
    }
	printf("element  not  found");
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/8968d7c5-51aa-4b50-a401-e54a69aa43be)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 4A
# DATE:
## Write a C program to break the 70089 into smallest possible number of bank notes.
(Note: The possible banknotes are 100, 50, 5, 2 and 1).
## AIM:
To Write a C program to break the 70089 into smallest possible number of bank notes.
(Note: The possible banknotes are 100, 50, 5, 2 and 1).

## PROGRAM:
```
#include <stdio.h>
int main() {
	int amt=70089, total;
	total = (int)amt/100;
	printf("There are: ");
	printf("\n%d Note(s) of 100.00\n", total);
	amt = amt-(total*100);
	total = (int)amt/50;
	printf("%d Note(s) of 50.00\n", total);
	amt = amt-(total*50);
	total = (int)amt/5;
	printf("%d Note(s) of 5.00\n", total);
	amt = amt-(total*5);
	total = (int)amt/2;
	printf("%d Note(s) of 2.00\n", total);
	amt = amt-(total*2);
	total = (int)amt/1;
	printf("%d Note(s) of 1.00\n", total);
	return 0;
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/d6408515-f24c-4ea1-b33e-46e2234ba03e)


## RESULT:
Thus, the above program is executed successfully.
# EX.NO: 4B
# DATE:
## Write a program in C to read any Month Number in integer and display the number of days for this month using a switch case.

## AIM:
To Write a program in C to read any Month Number in integer and display the number of days for this month using a switch case.
## PROGRAM:
```
#include <stdio.h>

int main() {
    int month;

    scanf("%d", &month);
    switch (month) {
        case 1: case 3: case 5: case 7: case 8: case 10: case 12:
            printf("31 days.\n");
            break;
        case 4: case 6: case 9: case 11:
            printf("30 days.\n");
            break;
        case 2:
            printf("February -28 days.\nin leap year The February month  Have 29 days.");
            break;
        default:
            printf("invalid Month number.\nPlease try again ....");
    }

    return 0;
}


```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/c879bcd2-bb89-47c7-b092-f2ea2bc0671f)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 4C
# DATE:
## To convert the string 'INDIA' into lowercase
## AIM:
To  convert the string 'INDIA' into lowercase

## PROGRAM:
```
#include <stdio.h>
#include <string.h>
int main()
{
  char str[30];
  
  scanf("%[^\n]", str);
  int i = 0;
  while (str[i] != '\0')
  {
    if (str[i] > 64 && str[i] < 91) 
      str[i] += 32;
    i++;
  }
  printf("Lower case String is:%s", str);
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/8f3cb5f0-cf7a-4bee-91f1-9f4d316faa85)


## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 4D
# DATE:
## Write a C program to convert a string from lowercase to uppercase 
## AIM:
Write a C program to convert a string from lowercase to uppercase 
## PROGRAM:
```
#include<stdio.h>
#include<string.h>
int main()
{
    int i;
    char a[100];
    scanf("%[^\n]",a);
    for(i=0;i<=strlen(a);i++)
    {
        if(a[i]>='a'&&a[i]<='z')
        {
            a[i]=a[i]-32;
        }
    }
    printf("%s",a);
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/9f063acf-75fc-40d1-ad39-ff8b2ea33b51)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 5A
# DATE:
## write a c program to find factorial of the number  '10' using pointer:


## AIM:
To Write a C program to convert a string from lowercase to uppercase 
## PROGRAM:
```
# include <stdio.h>
int  main( )
{
int  num, fact=1 ;
int  *pn, *pf ;

scanf("%d",&num) ;

pn = & num ;
pf = & fact ;

do
{
*pf = ( *pf ) * ( *pn ) ;
*pn = *pn - 1 ;
}while(  *pn > 0) ;
printf("Factorial of entered number is : %d ",*pf) ;
return 0;
}
```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/48a7a1d6-e903-4faf-8f8d-7353aaa73e70)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 5B
# DATE:
## Write a C program to swap any three values using function pointers (using a temporary variable) 

## AIM:
To Write a C program to swap any three values using function pointers (using a temporary variable) 
## PROGRAM:
```
#include <stdio.h>
void swap (int *a, int *b, int *c);
int main() 
{
  int m, n, o;
  scanf ("%d%d%d", &m, &n, &o);
  printf("m is %d, n is %d, o is %d\n", m, n, o);
  printf("m is %d, n is %d, o is %d\n", n,o,m);
  return 0;
}
void swap (int *a, int *b, int * c) 
{
  
  *c = *a - (*b + *c);
  *a = *a - (*b + *c);
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/cb3633f7-c7d8-4a28-9fcc-24b40676cb35)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 5C
# DATE:
## Write a C Program to print the Opposite Diagonal Elements of a Matrix[3x3]
## AIM:
To Write a C Program to print the Opposite Diagonal Elements of a Matrix[3x3]
## PROGRAM:
```
#include <stdio.h>
void swap (int *a, int *b, int *c);
int main() 
{
  int m, n, o;
  scanf ("%d%d%d", &m, &n, &o);
  printf("m is %d, n is %d, o is %d\n", m, n, o);
  printf("m is %d, n is %d, o is %d\n", n,o,m);
  return 0;
}
void swap (int *a, int *b, int * c) 
{
  
  *c = *a - (*b + *c);
  *a = *a - (*b + *c);
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/eb4ccf1b-8897-4b0c-8ce1-8dec108d4f8a)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 5D
# DATE:
## Write C program for the below half diamond string pattern in C.
## AIM:
To Write C program for the below half diamond string pattern in C.
## PROGRAM:
```
#include <stdio.h>
#include <string.h>

int main() {
    char str[100];
    
    scanf("%s", str);
    
    int len = strlen(str);
    
    // Upper half
    for(int i = 0; i < len; i++) {
        for(int j = 0; j <= i; j++) {
            printf("%c", str[j]);
        }
        printf("\n");
    }
    
    // Lower half
    for(int i = 1; i < len; i++) {
        for(int j = i; j < len; j++) {
            printf("%c", str[j]);
        }
        printf("\n");
    }
    
    return 0;
}


```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/f4797eac-d4b1-4d72-a9bc-8bfe53dcf2ea)

## RESULT:
Thus, the above program is executed successfully.

# EX.NO: 6A
# DATE:
## write a c program to find sum and average in the range from 70 to 85 using pointer.
## AIM:
To write a c program to find sum and average in the range from 70 to 85 using pointer.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    float a,b,sum,average;
    float *A=&a, *B=&b, *s=&sum, *av=&average;
    scanf("%f %f ",&a,&b);
    for (int i=*A; i<=*B; i++)
    {
        *s+=i;
    }
    
    *av=*s/(*B-*A+1);
    printf("Sum= %.2f, Average= %.2f",*s,*av);
    
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/54b08177-09eb-4470-95ff-af2fb616951e)

## RESULT:
Thus, the above program is executed successfully.


# EX.NO: 6B
# DATE:
## Write a C program to add two floating point numbers using pointers in which memory allocated using malloc(). 
## AIM:
To Write a C program to add two floating point numbers using pointers in which memory allocated using malloc(). 
## PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>

int main()
{
    float a,b,*ptr;
    scanf("%f %f",&a,&b);
    ptr=(float*)calloc(2,sizeof(float));
    if (ptr==NULL)
    printf("Memory not allocated");
    else
    {
        *ptr=a;
        *(ptr+1)=b;
        printf("%.6f ",*ptr+*(ptr+1));
    }
 
}

```
## OUTPUT:
![image](https://github.com/Gokhulraj2005/fundamentals-of-c/assets/138849253/c05bf783-7d99-4b89-ba1f-6f943dac6970)

## RESULT:
Thus, the above program is executed successfully.
