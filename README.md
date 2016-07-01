# Balan Lib
This is the java code about balan algorithm convert infix to postfix and calculated values. I also build a jar file library for the other Project.
We can carry out simple expression as +, -, *, / and complex as the square root 2, square root n th root, calculate the value of expression with parentheses, combinatorial, unconformity,...

![alt tag](http://i.imgur.com/Jhgal9t.png?1)

Example code to use

```java
package test;

import nguyenvanquan7826.com.Balan;

public class Main {
	public static void main(String[] args) {
		Balan balan = new Balan();
		String math = "(1+4)/5 + sqrt(9) - sin 30 + 5nCr3";
		System.out.println(balan.valueMath(math));
	}
}
```
## Other method

- isNumber(String s) : return true if s is a number else false
- isNumber(char c): return true if c is a number else false
- numberToString(double num, int radix, int len): return a string for number in radix (2, 8, 10, 16)
- postFix(String math): return a string is postfix of math
- primeMulti(double num): returns a string is prime factors of num
- round(double num, int len): round num with len after dot.
- valueMath(String math): calculator string math
- getRadix() và setRadix(int): get and set radix (hệ 2, 8, 10, 16).
- isDegOrRad() và setDegOrRad(boolean): Deg -> true and Rad -> false.

## My Project
[Calculator in Java link](http://www.nguyenvanquan7826.com/2014/06/11/java-chuong-trinh-calculator-may-tinh-bo-tui/)
