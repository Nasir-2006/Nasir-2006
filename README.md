# 👋 Hello! I'm Nasir 
## About Me
- 🔭 **Currently learning:** C Programming
- 🌱 **Focusing on:** Pointers and memory management
- 🎯 **Goal:** "I won't stop until I master C!"

## My C Program
#include<stdio.h>
void prime(int num);
int main(){

    int num;
    printf("Enter num:");
    scanf("%d",&num);
    prime(num);
}
void prime(int num)
{
    int pri=0;
   for(int i=1;i<=num;i++)
   {
    if(num%i==0)
    {
       pri++; 
    }
   }
   if(pri==2)
   printf("Hurrah!");
   else
   printf("Koi baat nahi dobara try kar le"); 
}

