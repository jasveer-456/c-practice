##  Task: Print Multiplication Table

###  Objective

Write a C program that  multiplication table up to 10 using a `for` loop.

---

###  Requirements

* Take an integer number
* Use a `for` loop
* Print the table from 1 to 10
## source code
## input
```
#include <stdio.h>

int main (){
	int i;
	int num =5;
	for (i=1;i<=10;i++)
	{
		int result = num*i;
		printf("%d * %d = %d\n",num,i,result);
	}
}
```
## output
```
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
5 * 4 = 20
5 * 5 = 25
5 * 6 = 30
5 * 7 = 35
5 * 8 = 40
5 * 9 = 45
5 * 10 = 50
```
