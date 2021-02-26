## 實習課第一題
```C
#include <stdio.h>
int main()
{
	int n;
	scanf("%d", &n);
	printf("%d=50*%d+5*%d+1*%d\n", n, n/50, n%50/5, n%50%5/1);
}

```
## 第二題
```C
#include <stdio.h>
int main()
{
	int a;
	scanf("%d", &a);
	int r = 0;
	for( int i=1;i<=a; i++)
	{
		if(a%i==0)
		{
			r++;
		}
	}
	printf("%d\n", r);
}
```
## 第3題
#include <stdio.h>
int main()
{
	int n;
	scanf("%d", &n);
	if( n>=90 )printf("A\n");
	else if ( 90>n&&n>=80 )printf("B\n");
	else if ( 80>n&&n>=60 )printf("C\n");
	else printf("F\n");
}
```
