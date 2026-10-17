Operators in PHP
Definition
An operator is a symbol or keyword that performs an operation on one or more values (operands).
1. Arithmetic Operators
Used for mathematical calculations.
Operator	Meaning	Example
+	Addition	$a + $b
-	Subtraction	$a - $b
*	Multiplication	$a * $b
/	Division	$a / $b
%	Remainder	$a % $b
**	Exponentiation	$a ** $b


<?php
$a = 10;
$b = 3;
echo $a + $b; // 13
echo $a % $b; // 1
?>
2. Assignment Operators
Used to assign or update values.
Operator	Example	Equivalent
=	$a = 5	Assign 5
+=	$a += 2	$a = $a + 2
-=	$a -= 2	$a = $a - 2
*=	$a *= 2	$a = $a * 2
/=	$a /= 2	$a = $a / 2


3. Comparison Operators
Compare values and return a Boolean result (true or false).
- == equal in value
- === equal in value and type
- != or <> not equal
- !== not identical
- > greater than
- < less than
- >= greater than or equal to
- <= less than or equal to
4. Logical Operators
- && or and — logical AND
- || or or — logical OR
- ! — logical NOT
- xor — true when exactly one condition is true
5. Increment and Decrement
- ++$a / $a++ — increment by one
- --$a / $a-- — decrement by one
6. String Operators
- . joins strings.
- .= appends a string to an existing string.
<?php
$first = "Hello";
$second = "PHP";
echo $first . " " . $second;
?>
Output: Hello PHP
7. Conditional (Ternary) Operator
<?php
$age = 20;
$result = ($age >= 18) ? "Adult" : "Minor";
echo $result;
?>
Output: Adult
Conclusion
PHP operators are used for calculations, assigning values, comparing values, combining conditions, and joining strings.
