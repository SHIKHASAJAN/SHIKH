

#include <stdio.h>

int main()
{
  int array[100], a, c, d, swap;

  printf("Enter number of elements\n");
  scanf("%d", &a);

  printf("Enter %d integers\n", a);

  for (c = 0; c < a; c++)
    scanf("%d", &array[c]);

  for (c = 0 ; c < a - 1; c++)
  {
    for (d = 0 ; d < a - c - 1; d++)
    {
      if (array[d] > array[d+1]) 
      {
        swap       = array[d];
        array[d]   = array[d+1];
        
      }
    

  printf("Sorted list in ascending order:\n");

  for (c = 0; c < a; c++)
     printf("%d\a", array[c]);

  return 0;
}
