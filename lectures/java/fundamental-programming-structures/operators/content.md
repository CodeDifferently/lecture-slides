# Operators









-
-
## What we'll cover
<p class="fragment fade-up">Operators</p>
<p class="fragment fade-up">Arithmetic Operators</p>
<p class="fragment fade-up">Relational Operators</p>
<p class="fragment fade-up">Parenthesis and Operator Hierarchy</p>
<p class="fragment fade-up">Syntactic Sugar</p>
<p class="fragment fade-up">Bitwise Operators</p>



-
-
### Operators
* An _operator_ is a symbol which denotes a _function_ to be done.
* An operator is followed by at least one _operand_.
* _operands_ are the _value_ (literal or variable) being _operated_ on.



-
-
### the 5 Arithmetic Operators
1. `+` addition
2. `-` subtraction
3. `*` multiplication
4. `/` division
5. `%` modulo


-
#### Arithmetic Operators<br>Addition
* The addition _operator_ has two _operands_:
    * _augend_ is the base value
    * _addend_ is the value to add to the base value
* By _adding_ values, we obtain their _sum_.

```java
int augend = 5;
int addend = 10;
int sum = augend + addend; // `sum` is 15
```




-
#### Arithmetic Operators<br>Subtraction
* The subtraction _operator_ has two _operands_:
    * _minuend_ is the base value
    * _subtrahend_ is the value to remove from the base value
* By _subtracting_ values, we obtain a _difference_.

```java
int minuend = 15;
int subtrahend = 10;
int difference = minuend - subtrahend; // `difference` is 5
```





-
#### Arithmetic Operators<br>Multiplication
* The multiplication _operator_ has two _operands_:
    * _multiplicand_ is the base value
    * _multiplier_ is the value to remove from the base value
* By _multiplying_ values, we obtain a _product_.

```java
int multiplicand = 5;
int multiplier = 10;
int product = multiplicand * multiplier; // `product` is 50
```






-
#### Arithmetic Operators<br>Division
* The divison _operator_ has two _operands_:
    * _dividend_ is the base value
    * _divisor_ is the value to remove from the base value
* By _dividing_ values, we obtain a _quotient_.

```java
int dividend = 10;
int divisor = 5;
int quotient = dividend + divisor; // `quotient` is 2
```





-
#### Arithmetic Operators<br>Modulo
* The modulo _operator_ has two _operands_:
    * _dividend_ is the base value
    * _divisor_ is the value to remove from the base value
* By _modding_ values, we obtain a _remainder_.

```java
int dividend = 10;
int divisor = 5;
int remainder = dividend + divisor; // `quotient` is 2
```




-
-
#### Binary Relational Operators
* 5 relational operators that compare two numbers and return a boolean value.
* Each operand is a predicate the result is a logical value
* The relational operators are < , > , <= , >= , == , and != 






-
###Combining Assignment with Operators

`x += 4;` is equivalent to `x = x + 4;`

-

###Increment and Decrement Operators

n++ adds 1 to the current value of the variable n, and n-- subtracts 1 from it

```
int n = 12; n++;
```

-

```
int m = 7;
int n = 7;

int a = 2 * ++m; // now a is 16, m is 8
int b = 2 * n++; // now b is 14, n is 8
b--;             // now b is 13
int k = b - 1;   // b is 13, k is 12
```



-
###Relational and boolean Operators

To test for equality, use a
double equal sign, ==.

```
3==7 // is false.

100 == 100 // is true
```
Use a != for inequality.

```
3!=7 // is true.

5 != 5 // is false
```

-

| boolean Operators |                       |
| ----------------- |:--------------------- |
| <                 | Less than             |
| >                 | Greater than          |
| <=                | Less than or equal    |
| >=                | Greater than or equal |

```
a < b
100 > 5
currentHeight <= maximumHeight
```

-

Java uses && for the logical “and” operator and || for the logical “or” operator.

The exclamation point ! is the logical negation operator.

-

The && and || operators are evaluated in “short circuit” fashion

The second argument is not evaluated if the first argument already determines the value

`expression1 && expression2`

```Java
input1.isAvailable && input1.canBeUsed()

(5 != 6) && (i == 0)

boolean a = true;
boolean b = false;

a && b         // false
a || b         // true
b || a         // true
!(a && b)      // true
```

-

The value of expression1 || expression2 is automatically true if the  first
expression is true, without evaluating the second expression. This is the so-called "short circuit" evaluation.

-

Java supports the ternary ?: operator

`condition ? expression1 : expression2`

commonly used when an **if** statement is too verbose

```
x < y ? x : y // gives the smaller of x and y

```

-

###Bitwise Operators

& ("and") | ("or") ^ ("xor") ~ ("not")

\>> and << operators which shift a bit pattern to the right or left.

\>>> operator  lls the top bits with zero, unlike >> which extends the sign
bit into the top bits. There is no <<< operator.

-
###Bitwise Example

12 = 00001100 (In Binary)

25 = 00011001 (In Binary)

Bitwise OR Operation of 12 and 25
  00001100
| 00011001
  ________
  00011101  = 29 (In decimal)
```
int number1 = 12, number2 = 25, result;

result = number1 | number2;
System.out.println(result);     // result is 29
```

-

###Parentheses and Operator Hierarchy

[Java order of operations](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)

`a && b || c`

 means

`(a && b) || c`

```
4 + 5 * 8 == 44
(4 + 5) * 8 == 72
```
`*, / have higher precedence than +, -`
-
Since += associates right to left, the expression

`a += b += c`

means

`a += (b += c)`

-