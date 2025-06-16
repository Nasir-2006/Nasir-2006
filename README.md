# 👋 Hello! I'm Nasir 
## About Me
- 🔭 **Currently learning:** C Programming
- 🌱 **Focusing on:** Pointers and memory management
- 🎯 **Goal:** "I won't stop until I master C!"

## My C Program
#include<stdio.h>
int main()
{
    int num,w1,w2,count=0;
    printf("Enter Number:");
    scanf("%d",&num);
   w1=num;
   w2=num;
    while(w1>=10)
    {
        w1=w1/10;
    }
    printf("First Digit:%d",w1);
    num=num%10;
    printf("\nLast Digit:%d",num);
    while(w2!=0)
    {
        w2=w2/10;
        count++;
    }
    printf("\nTotal Digits:%d",count);
}

