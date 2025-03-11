# IBB Ecodation Java Core

## Git 
```sh
git init
git add .
git commit -m "commit_message"
git push -u origin master
git clone "github links"
```
---

## Short Curt ()
```sh
Ctrl+/ : Single Comment => //
Shift+Ctrl+/ : Multiple Comment => /* */
Ctrl+Alt+l : Beautify => boşluk düzeltme
psvm+Tab: public static void main(String[] args) {}
sout+Tab: System.out.println(); => çıktı
Ctrl+d: copy and pase
Shift+F6: changing
```
---

## Java Operators
```sh
*Arithmetic Operators
+	Addition	Adds together two values	x + y	
-	Subtraction	Subtracts one value from another	x - y	
*	Multiplication	Multiplies two values	x * y	
/	Division	Divides one value by another	x / y	
%	Modulus	Returns the division remainder	x % y	
++	Increment	Increases the value of a variable by 1	++x	
--	Decrement	Decreases the value of a variable by 1	--x

*Java Assignment Operators
=	x = 5	x = 5	
+=	x += 3	x = x + 3	
-=	x -= 3	x = x - 3	
*=	x *= 3	x = x * 3	
/=	x /= 3	x = x / 3	
%=	x %= 3	x = x % 3	
&=	x &= 3	x = x & 3	
|=	x |= 3	x = x | 3	
^=	x ^= 3	x = x ^ 3	
>>=	x >>= 3	x = x >> 3	
<<=	x <<= 3	x = x << 3

*Java Comparison Operators
==	Equal to	x == y	
!=	Not equal	x != y	
>	Greater than	x > y	
<	Less than	x < y	
>=	Greater than or equal to	x >= y	
<=	Less than or equal to	x <= y

*Java Logical Operators
&& 	Logical and	Returns true if both statements are true	x < 5 &&  x < 10	
|| 	Logical or	Returns true if one of the statements is true	x < 5 || x < 4	
!	Logical not	Reverse the result, returns false if the result is true	!(x < 5 && x < 10)
```
--- 

## Java Math
```sh
*Math.max(x,y)
The Math.max(x,y) method can be used to find the "highest" value of x and y

Example:
Math.max(5, 10);

*Math.min(x,y)
The Math.min(x,y) method can be used to find the "lowest" value of x and y:

Example:
Math.min(5, 10);

*Math.sqrt(x)
The Math.sqrt(x) method returns the square root of x:

Example:
Math.sqrt(64);

*Math.abs(x)
The Math.abs(x) method returns the absolute (positive) value of x:

Example:
Math.abs(-4.7);

*Random Numbers
Math.random() returns a random number between 0.0 (inclusive), and 1.0 (exclusive):

Example:
Math.random();

** To get more control over the random number, for example, if you only want a random number between 0 and 100, you can use the following formula:

Example:
int randomNum = (int)(Math.random() * 101);  // 0 to 100

*Math.pow(x)
The pow() method raises a number to the power of another number.

Example:
Math.pow(2,5);

*Math.floor(x)
Rounds a number down (toward the lower integer).
It always rounds the number to the previous whole number.
Always decreases the value (rounds down).

Examples:
import math

// System.out.println(Math.floor(4.9));  # Output: 4
// System.out.println(Math.floor(4.1)); # Output: 4
// System.out.println(Math.floor(-2.5)); # Output: -3  (Rounds down for negative numbers as well)

*Math.ceil(x)
Rounds a number up (toward the next higher integer).
It always rounds the number to the next whole number.
Always increases the value (rounds up).
Examples:
import math

// System.out.println(Math.ceil(4.1));   # Output: 5
// System.out.println(Math.ceil(4.9));   # Output: 5
// System.out.println(Math.ceil(-2.5));  # Output: -2  (Rounds up for negative numbers) 

*Math.round(x,y)
Rounds a number to the nearest integer by default.
If a number is exactly halfway between two integers, it follows bankers rounding (rounds to the nearest even number).
You can also specify how many decimal places to round to.

Examples:
System.out.println(Math.round(4.3));  # Output: 4
System.out.println(Math.round(4.7)); # Output: 5
System.out.println(Math.round(4.5));  # Output: 4  (Rounds to the nearest even number)
System.out.println(Math.round(5.5));  # Output: 6  (Rounds to the nearest even number)

*Trigonometry
Math.sin(x) / Math.cos(x) / Math.tan(x) / Math.asin(x)

*Costant Numbers
System.out.println(Math.PI());
System.out.println(Math.E());

```
---

# Escape Character
```sh

```
---