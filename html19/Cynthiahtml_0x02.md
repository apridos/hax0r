1. The difference between declaration and initialization is
Declaration is the process of telling the C language compiler that we will create a variable. Declarations do not create variables; it only refers to the name of the variable and what type of data the variable will store, so memory is not allocated at the time of the declaration. whereas Initialization is when the value of a variable is used to determine the default value in a particular variable so that if we do not assign another value to the same variable, the value to be used is the default value.

2.
a.For Loop

#include <stdio.h>

int main()

{
  int i;
  int n;
  
  scanf("%d", &n);
  
  for (int i=1; i<n; i++)
  
  {
  	
    if (i% 4 == 0 || i% 3 == 0)
      
	  {
         
		 printf("%d\n", i);
      
	  }
  }
  return 0;
}

b.While Loop

#include <stdio.h>

int main ()

{
   int i = 1;
   int n;
   
   scanf("%d", &n);
   while (i < n)
   
   {
       if (i % 4 == 0 || i % 3 == 0)
       
   	printf ("%d\n", i);
       i++;
   }

   return 0;   
}

c.Do... While Loop

#include <stdio.h>

int main()

{
    int i = 1;
    int n;

    scanf("%d", &n);
    do
    {
        if (i % 4 == 0 || i % 3 == 0)
        printf ("%d\n", i);
        i++;
    }
    while (i <= n);
    return  0;
    
}
3.??
