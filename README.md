# genesis

#include<stdio.h>




int main()
{
int a,b,c,d,e,f;
a=30;
b=10;
//scanf("%d%d",&a,&b);
c=sum(a,b);
d=diff(a,b);
e=mul(a,b);
f=div(a,b);
printf("sum=%d\n diff=%d\nmultiple=%d\n div=%d",sum,diff,mul,div);

return 0;
}

int sum(int x,int y)
{ return x+y;
}
int diff(int x,int y)
{ 
  return x-y;
}
int mul(int x,int y)
{ 
  return x*y;
}
int div(int x,int y)
{ 
  return x/y;
}
