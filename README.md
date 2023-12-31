# JavaScript-Notes

## Global Scope(globalScope.js)

**Explanation:** We can see that the variable petName is declared in the global scope and is easily accessed inside functions. Also, the fruit was declared inside the function without any keyword so it was considered global and was accessible inside another function. 

## Local Varible(localVariable)
**Explanation:** We can see that the variable petName is declared in global scope but not initialized. Also, the functions are accessing the inner variable where each function has its own value for the variable petName.

Where to use which variable:

Although it may seem easier to use global variables than to pass data to a function and return data from it, global variables often create problems. That’s because any function can modify a global variable, and it’s all too easy to misspell a variable name or modify the wrong variable, especially in large applications. That, in turn, can create debugging problems.
In contrast, the use of local variables reduces the likelihood of naming conflicts. For instance, two different functions can use the same names for local variables without causing conflicts. That of course, means fewer errors and debugging problems. With just a few exceptions, then, all of the code in your applications should be in functions so all of the variables are local.
If you misspell the name of a variable that you’ve already declared, it will be treated as a new global variable. With this in mind, be sure to include the keyword when you declare new variables and always declare a variable before you refer to it in your code.


## JavaScript Comparison operators

**Equality (==):** Compares the equality of two operands. If equal then the condition is true otherwise false.

**Strict equality (===):** Compares the equality of two operands with type. If both value and type are equal then the condition is true otherwise false.

**Inequality (!=):** Compares inequality of two operands. True if operands are not equal.


## Logical Operators: 
These operators are used to determine the logic between variables or values.

**AND (&&):** The && operator returns true if both operands are true, otherwise, it returns false.

**OR (||):** The || operator returns true if at least one operand is true. It returns false only if both operands are false.

**NOT (!):** The ! operator is used to negate a Boolean value. It returns true if the operand is false, and false if the operand is true.
