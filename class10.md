# Readings : Debugging

To find the error source it help you to know how script processed and some task can't complete until another statement or function running because the interpreter is running line by line it sould be all the lines excuted correctly to running it. And the interpreter using the the excuation context consept.

Excuation context consept:
- GLOBAL CONTEXT: code in the script not in the function. and there is one global context in any page.
FUNCTION CONTEXT: code run within a function each function has its own context.
- EVAL CONTEXT (NOT SHOWN): It excuted like in an internal function.
VARIABLE SCOPE: first two execution contexts correspond with the notion of scope.
- GLOBAL SCOPE: variable declare outside a function.and it can be used anywhere in the code.
FUNCTION-LEVEL SCOPE: if the variable declare inside the function it can't be used outside that function.

the interpreter run one row in the time and if the code needs a data from another function it stacks or pills the new function. 

Each time a script enters a new execution context, there are two phases of activity:
- PREPARE: 
           - created the new scope.
           - Variables, functions, and arguments are created
           - The value of the this keyword is determined

- EXECUTE: 
           - Now it can assign values to variables
           - Reference functions and run their code
           - Execute statements

 > In JavaScript if the error happen it have an exception the interpreter stops and give the exception-handling.

 And there is Error objects You can ues it to find your mistakes in the code. And it will contain a property name,message,filenumber,linenumber.
and these error messages from the chrome browser, Other browsers' error messages may vary.

To deal with error you can debug the script to fix errors: track down the source of the error,
and fix it. and handel error gracefully:using try, catch, throw, and finally statements.

In the JavaScript it has a console will tell you when there is a problem with a script, and where to look for the problem, and what kind of issue it seems to be.

>If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.

[Home](README.md)



