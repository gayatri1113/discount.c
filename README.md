//# discount.c//
#include<stdio.h>
int main()
{
    int amt,dis,net;
    printf("enter amount");
    scanf("%d",&amt);
    dis=amt*0.10;
    net=amt-dis;
    printf("\ndiscount=%d",dis);
    printf("\nnet=%d",net);
    return 0;
}
