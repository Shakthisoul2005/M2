# EX-06 - Looping
## AIM:
Write a c program to find the sum of even digits using while loop 

## ALGORITHM:
```
1.Start
2.Declare variables: num, digit, and sum = 0
3.Read the number from the user
4.Repeat while num > 0:
  *Extract last digit using digit = num % 10
  *If digit % 2 == 0, add it to sum
   *Remove last digit using num = num / 10
5.Print the sum of even digits
6.Stop
```
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,count=1,s=0;
    scanf("%d",&n);
    while(count<=n)
    {
        if(count%2==0)
        {
            s=s+count;
        }
        count++;
        
    }
    printf("%d",s);
}
```

## OUTPUT:

![Screenshot 2025-04-29 180355](https://github.com/user-attachments/assets/937fc8b9-f701-4ecc-b294-55d6cad46b7e)










## RESULT:
Thus the program has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular Star pattern using loop.

## ALGORITHM:
```
1.Start
2.Declare variable n
3.Read the value of n (number of rows)
4.Use outer loop from 1 to n for rows
5.Use inner loop to print stars (*) in each row
6.Stop
```
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,i,j;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        for(j=a;j>=i;j--)
        {
            printf("*");
        }
        printf("\n");
    }
    
    
}
```

## OUTPUT:


![Screenshot 2025-04-29 180741](https://github.com/user-attachments/assets/3107b51d-b6d4-4fa6-aebe-7fdd7db249df)



## RESULT:

Thus the program has been executed successfully
 
 


# EX-08-Functions

## AIM:
Read N as input from the user. Write a C Program to print the sum of odd numbers from 1 to N


## ALGORITHM:
```
1.Start
2.Declare variables: N, i, and sum = 0
3.Read value of N from the user
4.Loop from i = 1 to N
  *If i is odd (i % 2 != 0), add it to sum
5.Print the value of sum
6.Stop
```
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,i,sum=0;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        if(i%2!=0)
        {
         sum+=i;
        }
        
        
    }
    printf("Sum of odd numbers from 1 to %d is %d",a,sum);
    
}
```

## OUTPUT:

![Screenshot 2025-04-29 181019](https://github.com/user-attachments/assets/b52d57d8-1368-4314-96ca-529ddb63b798)





## RESULT:

Thus the program  has been executed successfully
 
 


# EX-09-Use For Loop

## AIM:

Write a C program for finding the factorial of a given number using function with return type &  without arguments.

## ALGORITHM:
```
1.Start
2.Create a function int factorial() with return type and no parameters
3.Inside the function, read the number and calculate its factorial using a loop
4.Return the factorial result
5.In main(), call the function and store the returned result
6.Print the factorial and stop
```
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b,i;
    scanf("%d%d",&a,&b);
    b=1;
    for(i=1;i<=a;i++)
    {
        b=b*i;
    }
    printf("Factorial value is: %d",b);
}
```

## OUTPUT:

![Screenshot 2025-04-29 181227](https://github.com/user-attachments/assets/992553bb-3dd1-4859-a71d-676cb5dd5b78)



## RESULT:

Thus the program  has been executed successfully.




# EX – 10 - Factorial of a Number Using a Function
## AIM:
write a  program to convert 122.90 temperature from  Fahrenheit to Celsius?
## ALGORITHM:
```
1.Start
2.Declare fahrenheit and celsius as float
3.Assign 122.90 to fahrenheit
4.Apply the conversion formula
5.Print the result in Celsius
6.Stop
```


## PROGRAM:
```
#include <stdio.h>

int main() {
    float fahrenheit = 122.90;
    float celsius;

    celsius = (5.0 / 9.0) * (fahrenheit - 32);

    printf("Temperature in Celsius: %.2f°C\n", celsius);

    return 0;
}
```

## OUTPUT:
![Screenshot 2025-04-29 181521](https://github.com/user-attachments/assets/feffdb62-f54a-4af6-aab8-de9ad6c10f3d)

## RESULT:
The program has been executed successfully
 
