/*program that converts cups to pints*/
#include  <stdio.h>
int main(void)
{
   float cups;      /* the initial volume before the calculation*/
   float pints;
   float ounces;
   float Tb; float ts;
   
   printf(" enter the Volume you wish to convert in cups:\n");
   /* get the volume input from the user */
   scanf ("%f",  &cups);
   /* converts cups to pints and prints*/
   /* the other conversions follow*/
   pints = 0.5*cups;
   ounces = 8*cups;
   Tb = 16*cups;
   ts = 48*cups;
   /* we then show all the convertions together after the conversions*/
   printf("the number of pints for that volume is %d.\n", pints);
   printf("the number of ounces for that volume is %d.\n", ounces);
   printf("the number of Tablespoons for that volume is %d.\n", Tb);
   printf("the number of teaspoons for that volume is %d.\n", ts);
   printf("what a easy way to compare.\n");
   return 0;
   }
