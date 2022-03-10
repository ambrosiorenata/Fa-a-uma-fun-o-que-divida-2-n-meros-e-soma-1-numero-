# Fa-a-uma-fun-o-que-divida-2-n-meros-e-soma-1-numero-
#include <stdio.h>
#include <math.h>

int main()
{
   //Faça uma função que divida 2 números e soma 1 numero 
   
   int x, y, z, total;
   
   
   // Dados do usuario 
   printf("Digite o valor:");
   scanf("\n%d", &x);
   
   printf("Digite o valor:");
   scanf("\n%d", &y);
   
   printf("Digite o valor:");
   scanf("\n%d", &z);
   
   total = x/y+z;
   
  printf("\n %d", total);
   
   
    return 0;
}
