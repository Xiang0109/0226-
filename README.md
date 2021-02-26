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
