# 👋 Hello! I'm Nasir 
## About Me
- 🔭 **Currently learning:** C Programming
- 🌱 **Focusing on:** Pointers and memory management
- 🎯 **Goal:** "I won't stop until I master C!"

## My C Program
#include<stdio.h>
void swap(int*a,int*b)
// is function me int*a=&x or int*b=&y he
{
    *a = *a + *b - (*b=*a);
}
int main()
{
    int x,y;
    printf("Enter value of A and B\n");
    scanf("%d%d",&x,&y);
    swap(&x,&y);
    printf("A = %d\nB = %d",x,y);
}

