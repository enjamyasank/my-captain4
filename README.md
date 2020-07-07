# my-captain4
#include<studio.h>
int sum();
void main()
{int n;
printf("enter the value of n");
scanf("%d",&n);
sum(n)=sum(n)+n%10;
}
int sum(n)
{n=n/10;
return sum(n);
}
