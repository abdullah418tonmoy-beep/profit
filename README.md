//profit loss

#include<stdio.h>
int main()

{
    int a,b;

    printf("Enter your selling prize: ");
    scanf("%d",&a);
     printf("Enter your cost prize: ");
    scanf("%d",&b);

    if(a>b)
    {
        printf("profit\n");
    }

     else if(b>a)
    {
        printf("loss\n");
    }

     else if(a==b)
    {
        printf("no profit no loss\n");
    }

return 0;
}


