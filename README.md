#include<stdio.h>
int find_avg(int a,int b,int c)
{
    int avg=(a+b+c)/3;
    return avg;
}
int main()
{
    int a,b,c;
    printf("enter your number\n");
    scanf("%d %d %d",&a,&b,&c);
    int x= find_avg(a,b,c);
    printf("the average is %d", x);
    return 0;
}
