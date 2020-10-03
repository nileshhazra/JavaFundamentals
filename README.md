
<img alt="HTML" align="left" src = "https://cdn.freebiesupply.com/logos/thumbs/2x/java-4-logo.png" width = "82px"/>

# Java Fundamentals
> This Repository contains resources and documentation for understanding the fundamentals of Java Programming language for beginners.
## Variables

> The Table Below shows all primitive data types, size and range : 


| Type    	| Bytes 	| Range                       	|
|---------	|-------	|-----------------------------	|
| byte    	|   1   	| [-128, 127]                 	|
| short   	|   2   	| [-32768, 32767]             	|
| int     	|   4   	| [-2B, 2B]                   	|
| long    	|   8   	| [-9000000000B, 9000000000B] 	|
| float   	|   4   	| 6-7 Decimal                 	|
| double  	|   8   	| 14 Decimal                  	|
| char    	|   2   	| A, B, C, ...                	|
| boolean 	|   1   	| true / false                	|

>   By default Java See Numerical values as int and double therefore , when using long or float we have to add L and F at the end of the number.


>NOTE: String in Java is a reference data type and are immutable.
>
## Casting :
1. Implicit casting
```java
short x = 5;
int y = x + 10; 
```
   
2. Explicit casting
```java
double x = 1.1;
int y = (int) x + 2;
```
    