# javaScript book, Ch. 10, “Error Handling & Debugging”

### ORDER OF EXECUTION :
***To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex.***


 EXECUTION CONTEXTS :
***Every statement in a script lives in one of three 
execution contexts:***

- GLOBAL CONTEXT :
__Code that is in the script, but not in a function. 
There is only one global context in any page.__ 

+ FUNCTION CONTEXT :
__Code that is being run within a function. 
Each function has its own function context.__ 

* EVAL CONTEXT (NOT SHOWN) :
***Text is executed like code in an internal function 
called eva l {) (which is not covered in this book).*** 

- VARIABLE SCOPE :
__The first two execution contexts correspond with the 
notion of scope__: 

+ GLOBAL SCOPE :
__If a variable is declared outside a function, it can 
be used anywhere because it has global scope. 
If you do not use the var keyword when creating 
a variable, it is placed in global scope.__ 

* FUNCTION-LEVEL SCOPE 
***When a variable is declared within a function, 

### summary :
1. If you understand execution contexts (which have two 
stages) and stacks, you are more likely to find the error 
in your code. 

2. Debugging is the process of finding errors. It involves a 
process of deduction. 

3. The console helps narrow down the area in which the 
error is located, so you can try to find the exact error.

4. JavaScript has 7 different types of errors. Each creates 
its own error object, which can tell you its line number 
and gives a description of the error. 

5. If you know that you may get an error, you can handle 
it gracefully using the try, catch, finally statements. 
Use them to give your users helpful feedback. 
