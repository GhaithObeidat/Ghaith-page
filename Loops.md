## Comparasion and logical operators 

*A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.*

* Equal (==)	Returns true if the operands are equal.
* Not equal (!=)	Returns true if the operands are not equal.
* Strict equal (===)	Returns true if the operands are equal and of the same type.
* Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type.
* Greater than (>)	Returns true if the left operand is greater than the right operand.	
* Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.
* Less than (<)	Returns true if the left operand is less than the right operand.
* Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand.

## For and while loops 
### While loop

*The JavaScript while statement creates a loop that executes a block of code as long as the test condition evaluates to true.*

*The following illustrates the syntax of the while statement:*

while (expression) {

    // statement

 }

*The while statement evaluates the expression before each iteration of the loop.*

### For loop

*The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a block statement) to be executed in the loop.*

 *Use this statement:*

 *for ([ initialization]; [ condition]; [ final-expression]) statement*

 #### Initialization
*An expression (including assignment expressions) or variable declaration evaluated once before the loop begins. Typically used to initialize a counter variable. This expression may optionally declare new variables with var or let keywords. Variables declared with var are not local to the loop, i.e. they are in the same scope the for loop is in. Variables declared with let are local to the statement,
The result of this expression is discarded.*

#### condition
*An expression to be evaluated before each loop iteration. If this expression evaluates to true, statement is executed. This conditional test is optional. If omitted, the condition always evaluates to true. If the expression evaluates to false, execution skips to the first expression following the for construct.*

#### final-expression
An expression to be evaluated at the end of each loop iteration. This occurs before the next evaluation of condition. Generally used to update or increment the counter variable.

#### statement
A statement that is executed as long as the condition evaluates to true. To execute multiple statements within the loop, use a block statement ({ ... }) to group those statements. To execute no statement within the loop, use an empty statement (;).