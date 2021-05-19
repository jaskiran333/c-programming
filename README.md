# c-programming
WAP To find the divisor of a given number




#include <stdio.h>
#include <stdlib.h>

int main()
{
    int i,n;
    printf("Enter the integer:",n);
    scanf("%d",&n);
    printf("All the divisors of the integer are\n");
    for (i=1; i<=n; i++) {
    if (n%i==0)
      {
    printf("%d",i);
    
    printf("\n");
    }
      }
    return 0;
    }

