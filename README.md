#include<stdio.h>

int main()

{

//for q1and 3

  int i,j;

  for(i=0;i<6;i++)

  {

    for(j=0;j<6;j++)

    {

      if(j<=i)

      printf("01\t");

      else

      printf("\t");

     

    }

    printf("\n");

  }

   

   

  printf("\n\n");

//for q2

  int k,m;

  

  for(i=0;i<3;i++)

  {

    for(j=0;j<3;j++)

    {

      if(j>=i)

      printf("#\t");

      else

      printf("\t");

     

    }

    printf("\n");

  }

  printf("\n\n");

   

   

  return 0;

   

}
