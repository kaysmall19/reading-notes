Operators

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence

Arithmetic, Comparison, String, etc.

example 1
1 / 2; // 0.5
1 / 2 == 1.0 / 2.0; // this is true

Expressions

An expression is any valid unit of code that resolves to a value

The expression x=7 is an example of the first type. This expression uses te = operator to assign the value seven to the variable x.

JavaScript has the following expression categories:

Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.)

String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.)

Logical: evaluates to true or false. (Often involves logical operators.)

Primary expressions: Basic keywords and general expressions in JavaScript.

Left-hand-side expressions: Left values are the destination of an assignment.

Loops

Loops offer a quick and easy way to do something repeatedly.

Example 1

for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

There are a lot of loops in JavaScript, but they all essentially do the same thing.

But the main two are for and while.

for statement-repeats until a specified condition evealuates to *false*
while statement-executes its statements as long as a specified condition evaluates to true.
