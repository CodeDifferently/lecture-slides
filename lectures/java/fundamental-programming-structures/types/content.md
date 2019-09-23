# Title of Lecture









-
-
## What we'll cover
<p class="fragment fade-up">Data types</p>
<p class="fragment fade-up">Wrapper-Types</p>
<p class="fragment fade-up">The `null` object</p>
<p class="fragment fade-up">Control Flow</p>
<p class="fragment fade-up">Input and Output</p>
<p class="fragment fade-up">Arrays</p>














-
-
### Data Types
* What is a Data Type?
* Primitive Data Types
* Non-primitive Data Types 




-
#### What is a Data Type?
* In Java, every variable has a type.
* Variables are declared by first stating the _type_ of the variable, followed by the _name_ of the variable.
* Each _declaration_ is considered a _statement_
* Each _statement_ is followed by a semi-colon, `;`

```
double salary;
int vacationDays;
long earthPopulation;
boolean done;
int x;
```




-
#### Primitive Data Types
* A _primitive_ data type is ...
* There are 8 primitive data-types
    1. `double` variable type stores 
    2. `long` variable type stores large non-fractional _number_ values.
    3. `int` variable type stores non-fractional _number_ values.
    4. `char` - variable type stores a _character_ type
    5. `short` variable type stores non-fractional _number_ values.
    6. `short` variable type stores non-fractional _number_ values.
    7. `float`
    8. `boolean`



-
#### Non-primitive Data Types
* Discussion point 1C.1
* Discussion point 1C.2
* Discussion point 1C.3












-
-
### Conversions between Numeric Types
* Widening Primitive Conversions
* Narrowing Primitive Conversions
* Casting






-
### What is Widening Primitive Conversions?
* conversions of primitive types which do not lose information are named _widening primitive conversions_.
* A widening primitive conversion does not lose information about the overall magnitude of a numeric value.

```java
int n = 123456789;
float f = n; // f is 1.23456792E8
```



-
#### Specific Widening Primitive Conversions
* 19 specific conversions on primitive types:
    - `byte` to `short`, `int`, `long`, `float`, or `double`
    - `short` to `int`, `long`, `float`, or `double`
    - `char` to `int`, `long`, `float`, or `double`
    - `int` to `long`, `float`, or `double`
    - `long` to `float` or `double`
    - `float` to `double`



-
### What is Narrowing Primitive Conversions?
* conversions of primitive types which lose information are named _narrowing primitive conversions_.
* A widening primitive conversion may lose information about the overall magnitude of a numeric value.
* Narrowing primitive conversions are done by means of _casting_.


```java
double d = 9.997;
int n = (int) d; // n is 9
```






### Casts

When two values are combined with a binary operator (such as n + f where n is an integer and f is a floating-point value), both operands are converted to a common type before the operation is carried out.

- If either of the operands is of type double, the other one will be converted to a double.
- Otherwise, if either of the operands is of type float, the other one will be converted to a float.
- Otherwise, if either of the operands is of type long, the other one will be converted to a long.
- Otherwise, both operands will be converted to an int.






-
#### Sub-topic 2B
* Discussion point 2B.1
* Discussion point 2B.2
* Discussion point 2B.3


-
#### Sub-topic 2C
* Discussion point 2C.1
* Discussion point 2C.2
* Discussion point 2C.3













-
-
### Topic 3
* Sub-topic 3A
* Sub-topic 3B
* Sub-topic 3C



-
#### Sub-topic 3A
* Discussion point 3A.1
* Discussion point 3A.2
* Discussion point 3A.3


-
#### Sub-topic 3B
* Discussion point 3B.1
* Discussion point 3B.2
* Discussion point 3B.3


-
#### Sub-topic 3C
* Discussion point 3C.1
* Discussion point 3C.2
* Discussion point 3C.3













-
-
## Lecture Summary
* Topic 1 Summary
* Topic 2 Summary
* Topic 3 Summary
