## Loops

Need to repeat one or more operation? Use loop.

Consider the following output, 

```
This is a loop
1
2
3
4
5
6
```

You may write the code like this,

```
#include<stdio.h>

int main(){
printf("This is a loop\n");
printf("1\n");
printf("2\n");
printf("3\n");
printf("4\n");
printf("5\n");
printf("6\n");
return 0;
}
```
But how if I ask you to print 1 ... 1000? You won't do that with thousand lines of code right?

### Loop to the rescue


#### For loop

Here's the basic structure of for loop
```
...
printf("This is a loop\n");
for(int i = 1 ; i < 7 ; i++){	// This line called head
	printf("%d\n", i);	// the rest called body
}
...
return 0;
```

`int i = 0` you initialize `i` as zero right here. You may call `i` as iterator variable
`i < 7` look, you may change `7` to any integer or variable that store integer. Let's just assume you have initialize `x` as 10 before, now you can tell that `i < x` equals to `i < 10`.
`i++` is incremental operation, it will increase `i` by one for each **body** execution completed.

> The incremental operation executed once the **body** execution completed. 

You can also declare iterator variable **outside** the head.
```
... 
int i;
for(i = 0 ; i < 7 ; i++){
...
return 0;
```

#### While loop
```
...
printf("This is a loop\n");
int i = 0;
while(i < 7){
	printf("%d\n", i);
	i++;
}
return 0;
```
Look, you have to **declare and initialize** iterator variable **not in** the loop.
The incremental operation must be inside the body.


#### do ... while
```
...
printf("This is a loop\n");
int i = 0;
do{
	printf("%d\n", i);
	i++;
}while(i < 6);
return 0;
```

It's just look similar to **while loop**, but different. Look at the control variable, on **while loop** you have `7` and here you have `6`. But, why!?
On **do while loop**, it will execute the body **first** and then check for the condition. If the condition is still fulfilled, then it will execute the body again. If not, it will exit from the loop.

Consider following code,
```
...
do{printf("Hi!")}while(1!=1);
return 0;
...
```
It's clearly **not true** that **1!=1 (1 not equal to 1)**. But you'll find out that `Hi!` will be printed when you execute the code. When `Hi!` is already printed, then it will check the condition which is `false`, the body is not going to be executed again.














