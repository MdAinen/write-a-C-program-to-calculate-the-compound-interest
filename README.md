#include<stdio.h>
#include<math.h>


int main()
{
    float p,t,r,si,ci;
    printf("Enter principle amount (p): ");
    scanf("%f",&p);
    printf("\nEnter time in year (t): ");
    scanf ("%f",&t);
    printf("\nEnter rate in year (r): ");
    scanf("%f",&r);
    si=(p*t*r)/100.0;
    ci=p*(pow(1+r/100,t)-1);
    printf("\nSimple intrest = %0.3f \n",si);
    printf("Compound intrest=%0.3f \n",ci);
    return 0;
}
