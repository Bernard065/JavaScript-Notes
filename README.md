# JavaScript-Notes

## Global Scope(globalScope.js)

**Explanation:** We can see that the variable petName is declared in the global scope and is easily accessed inside functions. Also, the fruit was declared inside the function without any keyword so it was considered global and was accessible inside another function. 

## Local Varible(localVariable)
**Explanation:** We can see that the variable petName is declared in global scope but not initialized. Also, the functions are accessing the inner variable where each function has its own value for the variable petName.

Where to use which variable:

Although it may seem easier to use global variables than to pass data to a function and return data from it, global variables often create problems. That’s because any function can modify a global variable, and it’s all too easy to misspell a variable name or modify the wrong variable, especially in large applications. That, in turn, can create debugging problems.
In contrast, the use of local variables reduces the likelihood of naming conflicts. For instance, two different functions can use the same names for local variables without causing conflicts. That of course, means fewer errors and debugging problems. With just a few exceptions, then, all of the code in your applications should be in functions so all of the variables are local.
If you misspell the name of a variable that you’ve already declared, it will be treated as a new global variable. With this in mind, be sure to include the keyword when you declare new variables and always declare a variable before you refer to it in your code.