#include<stdio.h>
float table(float a);
float main()
{
    float a,b,k;
    printf("Enter the value");
    scanf("%f",&a);
    table(a);
    
}
float table(float a)
{
    for( float b=1;b<=10;b++)
    {
        printf("\t%f",b*a);
    }
}
