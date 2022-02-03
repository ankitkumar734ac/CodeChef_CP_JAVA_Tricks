# O(1) Operation For Some Functions

### EVEN & ODD
```
System.out.println((a & 1) == 0 ?  "EVEN" : "ODD" );
```
### Multiply by 2 OR Division by 2 
```
n = n << 1;   // Multiply n with 2
n = n >> 1;   // Divide n by 2
```
### Swapping of 2 numbers
```
a ^= b;
b ^= a;
a ^= b; 
```
### Calculating the number of digits 
```
int count = (int) Math.floor(Math.log10(N)) + 1;
```
### Efficient trick to know if a number is a power of 2 
```
/* Method to check if x is power of 2*/
static boolean isPowerOfTwo (int x)
{
	/* First x in the below expression is	for the case when x is 0 */
	return x!=0 && ((x&(x-1)) == 0);
}
```

