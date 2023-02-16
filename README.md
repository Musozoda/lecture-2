# **Table of Contents**
### *1. Functions*
### *2. Scope*
### *3. Hoisting*
### *4. Recursion and Closure*

___
___

                                          1.Functions
![function](https://masteringjs.io/assets/logo.png) 

> A JavaScript function is a block of code > designed to perform a particular task.
> ___
>A JavaScript function is executed when  "something" invokes it (calls it).

## Function Decloration

Declared functions are not executed immediately. They are "saved for later use", and will be executed later, when they are invoked (called upon).

## Function Expression

- A function expression can be stored in a variable:
-  the variable can be used as a function:

                                          2.Scope
![scope](https://lh3.googleusercontent.com/proxy/wOcIrKvn-3uP-hKAm5Wx4qdiJlaNCrKTZC2KNMyjdAtfnyUKQ_6QHpMxM-eUTAhC1_dGG5Uv5P16rXPcTxQWIKWm7oMWai7NIbahcmSX3_X-YM9-vMnIS-b2Y2NSlbJxX3GBRfxmmQ_4ikP9HbRQSZPiOxEbT4plz5rHtHVud2_7mFYh=w1200-h630-p-k-no-nu)
JavaScript has 3 types of scope: 
1. Block scope
2. Function scope
3. Global scope

___

Block Scope :

- Before ES6 (2015), JavaScript had only     Global Scope and Function Scope.

- ES6 introduced two important new           JavaScript keywords: let and const.

- These two keywords provide Block Scope in   JavaScript.

- Variables declared inside a { } block      cannot be accessed from outside the block:

___

 Local Scope :
 - Variables declared within a JavaScript function, become LOCAL to the function.

> Local variables have Function Scope:
>> They can only be accessed from within the function.

Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.

Local variables are created when a function starts, and deleted when the function is completed.

 ___
 
 Function Scope :
 
- JavaScript has function scope: Each function creates a new scope.

- Variables defined inside a function are not accessible (visible) from outside the function.

- Variables declared with var, let and const are quite similar when declared inside a function.

- They all have Function Scope:
 
 ___
 
 Global JavaScript Variables :
- A variable declared outside a function, becomes GLOBAL.

> A global variable has Global Scope:
>> All scripts and functions on a web page can access it.

___

 Global Scope :
- Variables declared Globally (outside any function) have Global Scope.

- Global variables can be accessed from anywhere in a JavaScript program.

- Variables declared with var, let and const are quite similar when declared outside a block.

- They all have Global Scope:

                                          3.Hoisting

*Hoisting is JavaScript's default behavior of moving declarations to the top.*

 JavaScript Declarations are Hoisted :
- In JavaScript, a variable can be declared after it has been used.

- In other words; a variable can be used before it has been declared.

> Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope (to the top of the current script or the current function).

                                          4.Recursion and Closure

# **Recursion**

![recursion](https://cdn-images-1.medium.com/max/1600/0*bvQZxV6MneLT_cI4.jpg)

> A recursive function must have a condition to stop calling itself. Otherwise, 
the function is called indefinitely.
>> Once the condition is met, the function stops calling itself. This is called the 
base condition.
>> > To prevent infinite recursion, you can use if...else statement (or similar 
approach) where one branch makes the recursive call, and the other 
doesn't

# **Closure**

![closure](https://edward-huang.com/images/what-is-really-so-special-about-javascript-closure-/Closure%20JS.png)

> Closure is one of the most 
important, and often least 
understood, concepts in 
JavaScript. You can think of 
closure as a way to 
“remember” and continue to 
access a function’s scope (its 
variables) even once the 
function has finished running.

![end](https://th.bing.com/th/id/R.7b883e27f562dd411d5b940ef208a791?rik=1Cvo4oixHnuLNQ&pid=ImgRaw&r=0)











