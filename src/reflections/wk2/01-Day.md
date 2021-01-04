# Monday 12-7-2020 JS > Var, let and const
_Daily Journal_ 

## What is Scope ? 

Scope refers to the context of the code and which variables are accessable to javascript 

There is also local scope and gobal scope.

Local variables are defined inside of the block 
Global variables are typically defined outside of the block 

## What is Hoisting ?

Hoisting is where the variables and functions that are declared are moved to the top of the script before it runs. This means that a variable can be used before it has been declared. 


## In what cases might you use let vs const vs var ? 

Let is  considered the preferred variable for declaration now.  You would want to use this to block the scope of the variable to only exists inside the block of code, rather than using var and having whatever is inside of the code block now be defined as such. You would want to use let when you are defining things that you only want to define inside of the scope of that block of code. 

Const variables are block scoped. Const are unable to be updated or re-declared. You would want to use a constant variable when you don't want it to be redeclared and you are not oging to reuse it again in the script

Var would be used if you want to define stuff for the entirety of your code. So if you are going to reuse a term inside of a code block, it may be beneficial. 



