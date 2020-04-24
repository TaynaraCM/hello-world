#include <cs50.h>
#include <stdio.h>

int main(void)
{
 int bloco;
 do{
 bloco = get_int("Número de blocos desejados\n");
   } while (bloco>10 || bloco<1);
 for (int i = 0; i<bloco; i++)
   {
       for (int j = 0; j<i+1; j++)
       {
      printf ("#"); 
   }
   printf("\n");
}
}
