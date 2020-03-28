1. **Declaration** : refers to the introduction of a new name in the program. For example, you can *declare* a new function by describing it's "signature".

   **Initialization** : refers to the "assignment" of a value, at construction time. For a generic object of type.
 
2.  **For Loop**

  '#include <stdio.h>'
  
'int main()'

'{'

'  int i;'

'  for(i=1;i<100;i++)'

'	{if(i%3==0 && i%4==0)'

		'printf ("%i\n",i);'
    
'	}'

'	 return 0;'

'}'


**While Loop**

'#include <stdio.h>' 

'int main()'

'{'

'  int i = 1;'

'  int j=100;'

'  while (!(i==j))'

'  {'

'	  if(i%3==0 && i%4==0)'

'	  printf("%i \n",i);'

'    i++;'  

'  }'

'  return 0;'

'}'


**Do...while Loop**

'#include <stdio.h>'

'int main()'

'{'

'  int i = 1;'

'  int j=100;'

'  do {'

'	  if(i%3==0 && i%4==0)'

'	  printf("%i \n",i);'

'    i++;'

'  }'

'  while (!(i==j));'

'  return 0;'

'}'

3.  '#include <stdio.h>' 

'int main()'

'{'

'  int i=1;'

'  int q;'

'  scanf("%d",&q);'

'  while (!(i==q)){'

'    printf("%i\n",i);'

'    i++;'

'  }'

'  return 0;'

'}'

4. Equal To Operator (==)

(==) is anEqual To Operator in C and C++ only

so, while(1==1) means while 1 equals 1 the value is true
