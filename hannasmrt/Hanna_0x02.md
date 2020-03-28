1. The difference between __declaration__ and __initialization_ is declaration means creating a variable used in a program
must be declare, while initialization means declaring a variable and assigning a value at the declaration time called
_initializing a variable_.
2. __FOR LOOP, WHILE LOOP, DO...WHILE
__For__
#include<stdio.h>

int main()
{
	int i;
	for(i=1 ; i<=100 ; i++)
	{
		if (i%3==0 && i%4==0)
		printf("%d\n", i);
	}
		return 0;
}

__While__
#include<stdio.h>

int main()
{
	int i = 1;
	int j = 100;
	while(!(i==j))
	{
		if (i%3==0 && i%4==0)
		printf("%d\n", i);
		i++;
	}
	return 0;
}

__Do While__
#include<stdio.h>

int main()
{
	int i=1
	int j=100
	do{
		if(i%3=0 && i&4=0)
		print("%d\n", i);
		i++;
	}
	while (!(i==j));
	return 0;
}
__3.__
#include<stdio.h>

int main()
{
	int i=1
	int q;
	scanf("%d\n", &q);
	while (!(i==q)){
		printf("%d\n",1);
		i++;
	}
	return 0;
}

__4.__
(==) is an operator that tells the compiler to perform a certain mathematical or logical manipulation 
is While(1==1) mans that when the input is equal to 1 then it is true
