## Patricia’s

### 1. The difference between **_declaration_** and **_initialization_**.
  _Declaration_ of a variable specifies its name and datatype. Declaration does not create a variable; it's only refers to a variable name and what type of data the variable will hold, so memory is not allocated at the time of declaration.
  
  `int i; /* Declaration */`
  
  _Initialization_. When a variable is declared it contains undefined value commonly known as garbage value. If we want we can assign some initial value to the variable during the declaration itself, this is called initialization of the variable.
  
  `int i = 10;`

### 2. FOR LOOP, WHILE LOOP, AND DO... WHILE LOOP

 **For Loop**
 
  ```
  //patricia cuteee
  
  #include <stdio.h>
  
  int main()

{
    int i;
    int n;
    
    scanf("%d", &n);
    for (int i = 17 ; i < n ; i++)
    {
      if (i % 4 == 0 || i % 3 == 0)
        {
           printf("%d\n", i);
        }
    }
    return 0
}
```

 **While Loop**
 
 ```
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
```
**Do... While Loop**

```
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
```
