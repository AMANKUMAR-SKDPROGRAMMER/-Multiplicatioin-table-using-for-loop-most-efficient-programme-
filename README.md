#  Multiplicatioin table using for loop most efficient programme 
 AN MULTIPLICATION TABLE USING FOR LOOP THE MOST EFFICIENT PROGRAMME
#include<stdio.h>
int main()
{
    int a;
    printf("Enter the number you want multiplication table of \n");
    scanf("%d",&a);
    
    printf("the multiplicatioin table of entered number is %d\n",a);



    for (int i = 1; i < 11; i++)
    {
      
      printf("%d x %d = %d\n", a, i, a * i);

    }
    
}