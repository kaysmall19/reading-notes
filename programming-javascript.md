<h2>Control Flow</h2>

The control flow is the order in which the computer executes statements in a script.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

if (field==empty) {
    promptUser();
} else {
    submitForm();
}

Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

<h2>Javascript Functions</h2>

A Javascript function is a block of code designed to perform a particular task.

A Javascript function is executed when *something* invokes it (calls it).

A Javascript function is defined with the *function* keyword, follwed by **name**, follwed by parentheses().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

<h3>Function Return</h3>

When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

<h3>Javascript Operators</h3>

The multiplication operator (*) multiplies numbers.

The addition operator (+) adds numbers:

The assignment operator (=) assigns a value to a variable.

<h4>Javascript Arithmetic Operators</h4>

Arithmetic operators are used to perform arithmetic on numbers:

Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement

<h4>JavaScript Assignment Operators</h4>

Assignment operators assign values to JavaScript variables.

Operator	Example	Same As
=	x = y	x = y
+=	x += y	x = x + y
-=	x -= y	x = x - y
*=	x *= y	x = x * y
/=	x /= y	x = x / y
%=	x %= y	x = x % y
**=	x **= y	x = x ** y

JavaScript Comparison Operators

Operator	Description
==	equal to
===	equal value and equal type
!=	not equal
!==	not equal value or not equal type
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to
?	ternary operator