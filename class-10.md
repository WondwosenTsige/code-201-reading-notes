
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 10 reading notes

### JS Debugging

- __Debugging__ *is the process of finding errors. It involves a process of deduction.*

- When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but *you also need to create the instructions that allow the computer to solve it, too.*

- When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it. Here, we will discuss about:

    - __THE CONSOLE & DEV TOOLS:__ Tools built into the browser that help you hunt for errors.

    - __COMMON PROBLEMS:__ Common sources of errors, and how to solve them.

    - __HANDLING ERRORS:__ How code can deal with potential errors gra cefully.

- __ORDER OF EXECUTION:__ To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

- The JavaScript interpreter uses the concept of *execution contexts.* There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

- __EXECUTION CONTEXT:__ *Every statement in a script lives in one of three execution contexts:*

    1. *GLOBAL CONTEXT:* Code that is in the script, but not in a function. There is only one global context in any page

    2. *FUNCTION CONTEXT:* Code that is being run within a function. Each function has its own function context

    3. *EVAL CONTEXT (NOT SHOWN):* Text is executed like code in an internal function called eval()

- __VARIABLE SCOPE:__ The first two execution contexts correspond with the notion of scope

    1. *GLOBAL SCOPE:* If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.

    2. *FUNCTION-LEVEL SCOPE:* When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

- _The stack_
    - *The javascript interpreter processes one line of code at a time. when a statement needs data from another function, it stacks(or piles) the new function on top of the current task*

- *Error objects can help you find where your mistakes are and browsers have tools to help you read them.*

- The console helps narrow down the area in which the error is located, so you can try to find the exact error.

- __JavaScript has 7 different types of errors.__ Each creates its own error object, which can tell you its line number and gives a description of the error.

- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.




















[>> NEXT (class 11 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-11)


