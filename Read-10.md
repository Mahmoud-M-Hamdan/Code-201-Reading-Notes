# JS 
## 

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:

This script above creates a greeting message, then
writes it to an alert box (see right-hand page). In
order to create that greeting, two functions are used:
greetUser () and getName () .
You might think that the order of execution (the
order in which statements are processed) would be
as numbered: one through to four. However, it is a
little more complicated.
To complete step one, the interpreter needs the
results of the functions in steps two and three
(because the message contains values returned by
those functions). The order of execution is more like
this: 1, 2, 3, 2, 1, 4.

1. The greeting variable gets its value from the
greetUser() function.
2. greetUser() creates the message by combining
the string 'He 11 o ' with the result of getName ().
3. getName () returns the name to greetUser() .
2. greetUser() now knows the name, and combines
it with the string. It then returns the message to the
statement that ca lled it in step 1.
1. The va lue of the greeting is stored in memory.
4. This greeting variable is written to an alert box.

## EXECUTION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

EXECUTION CONTEXT
JavaScript
Hello Molly
Every statement in a script lives in one of three
execution contexts:
Q GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
Q EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eva l {) (which is not covered in this book).
VARIABLE SCOPE
The first two execution contexts correspond with the
notion of scope (which you met on p98):
Q GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.

## EXECUTION CONTEXT & HOISTING

Understanding that these two phases happen helps
with understanding a concept called hoisting. You
may have seen that you can:
• Call functions before they have been declared
(if they were created using function declarations

• Assign a value to a va ria ble that has not yet been
declared
This is because any variables and functions within
each execution context are created before they are
executed.
The preparation phase is often described as taking
all of the variables and functions and hoisting them
to the top of the execution context. Or you can think
of them as having been prepared.
Each execution context also creates its own
vari ab 1 es object. This object contains details of all
of the variables, functions, and parameters for that
execution context.
8 ERROR HANDLING & DEBUGGING
2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements
You may expect the following to fail, because
greetuser() is called before it has been defined:
var greeting= greetUser{);
function greetUser() {
II Create greeting
It works because the function and first statement are
in the same execution context, so it is treated like this:
function greetUser()
II Create greeting
}
var greeting= greetUser{);
The following would would fail because greetuser()
is created within the getName () function's context:
var greeting= greetUser();
function getName() {
function greetUser()
II Create greeting
}
II Return name with greeting

