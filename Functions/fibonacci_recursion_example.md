# PSAT 

## Recursion Function - Fibonacci

```
f1=0;
f2=1;
	
fibo(f1,f2,n)

fibo(int f1, int f2, int n)
{
	if(n==0)
		return 0;
	else
		int res;
		res=f1+f2;
		print f1;
		fibo(f2,res,n-1);		 
}
```

## Explanation

fibo(0,1,4)

	res = 0+1 = 1 > 0
	fibo(1,1,3)

fibo(1,1,3)
	
	res = 1+1 = 2 => 1
	fibo(1,2,2)
	
fibo(1,2,2)

	res = 1+2 = 3 => 1
	fibo(2,3,1)
	
fibo(2,3,1)
	
	res = 2+3 = 5 => 2
	fibo(3,5,0)
	
