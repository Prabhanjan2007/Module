# Module 1
# day 1
Write a C program to initialize the value as 5.800000 & display the same value as 5.8.
# program 
```
#include <stdio.h>
int main()
{
    float a=5.800000;
    printf("%.1f",a);
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/0d0c8cbe-61bf-492b-9835-f1942fd9aedd" />

# day 2
Write a C program to read  N value and check that value is equal to 10 or not using if-else
# program
```
#include<stdio.h>
int main()
{
    int N;
    scanf("%d",&N);
    if(N!=10)
    {
        printf("Given number is NOT TEN.");
    }
    else
    {
        printf("Given number is TEN.");
    }
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/6d6f7380-0e80-49cf-b101-fc58b62b14cb" />

# day 3
Write a C program to calculate the diameter and circumference of circle.
# program
```
#include <stdio.h>
int main()
{
    float a;
    scanf("%f",&a);
    printf("Diameter of circle=%.2f units\nCircumference of circle=%.2f units",2*a,2*3.14*a);
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/802bc196-5fce-47ce-a6d7-9e56f9828f24" />

# day 4
Raju and Ramu purchased  a product  and they made a self analysis that if cost price and selling price of a product are input through the keyboard,Help them out to write a C program to determine whether the seller has made profit or incurred loss using IF-ELSE.
# program
```
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d\n%d",&a,&b);
    if((b-a)>0)
    {
        printf("Profit = %d",b-a);
    }
    else
    {
        printf("Loss = %d",a-b);
    }
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/05c01c6f-4b74-47e5-b224-51e68ccbfaa0" />

# day 4
Write a C program to check whether number is  even number and divisible by 3 or not using nested if.
# program
```
#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a%2==0)
    {
        printf("The number is even\n");
        if(a%3==0)
        {
            printf("The number is divisible by %d",3);
        }
        else
        {
            printf("The number Not divisible by %d",3);
        }
    }
    else
    {
        printf("The number is NOT an even number");
    }
    return 0;
    
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/921a6ee7-b929-475d-abd9-fc0690c55b62" />
