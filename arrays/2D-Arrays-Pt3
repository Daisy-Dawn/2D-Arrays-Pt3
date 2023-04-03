#include <stdio.h>
#include <stdlib.h>

int main(void)
{
	  int a[3][3], i, j, sr, sc, sum = 0;

	    printf("Enter Matrix:\n");

	      for (i = 0; i < 3; i++)
		          {
				        for (j = 0; j < 3; j++)
						        scanf("%d", &a[i][j]);
					    
			  }

	      printf("Your Matrix is:\n");
	        for (i = 0; i < 3; i++)
			    {
				          for (j = 0; j < 3; j++)
						          printf("%d\t\t", a[i][j]);
					        printf("\n");
						    }
		  for (i = 0; i < 3; i++)
			      {
				            sr = sc = 0;
					          for (j = 0; j < 3; j++)
						  {
							    sr = sr + a[i][j];
							      sc = sc + a[j][i];
						  }
						        printf("\nSum Row = %d, Sum Column = %d", sr, sc);
							    }
		  for (i = 0; i < 3; i++)
		  {
			  for (j = 0; j < 3; j++)
			  {
				  sum = sum + a[i][j];
			  }
		  }
		  printf("\n\nSum = %d\n", sum);
		    
}
