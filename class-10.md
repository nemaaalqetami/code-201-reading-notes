## Chapter 10 :







#### Error Handling & Debugging :







JavaScript can be hard to learn and everyone makes 
mistakes when writing it. We  will help you learn 
how to find the errors in your code. and teach you how 
to write scripts that deal with potential errors gracefully



The Stack :

The javascript interpreter proocesses one line of code at a time .
When a statment needs data from another function , it stacks(or piles)
the new function on top of the current task .


Execution Context & Hoisting :

Each time a script enters a new execution context, there are two phases 
of activity: 


1- Prepare .

- The new scope is created 
- Variables, functions, and arguments are created 
- The value of the this keyword is determined 


2- Execute . 



- Now it can assign values to variables 
- Reference functions and run their code 
- Execute statements 


Understanding Scope :


In the interpreter, each execution context has its own `variables` object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's `variables` object


Understanding Errors :

If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. 



Error Objects :


Error objects can help you find where your mistakes are 
and browsers have tools to help you read them. 


HOW TO DEAL WITH ERRORS :

Now that you know what an error is and how the browser treats them, 
there are two things you can do with the errors. 


1- Debug The script To Fix Errors :


If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 


2- Handle Errors Gracefully :

You can handle errors gracefully using try, catch, 
throw, and f i na 1 ly statements. 


Debugging WorkFlow :

Debugging is about deduction: eliminating potential causes of an error. 


Browser Dev Tools & Javascript Console :



The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 

* The JavaScript console is just one of several developer tools that are 
found in all modern browsers. 


How To Look At Errors in Chrome :

The console will show you when there is an 
error in your JavaScript. It also displays the line 
where it became a problem for the interpreter.



Weiting From The script To The Console :


Browsers that have a console have a console object, which has several 
methods that your script can use to display data in the console. 
The object is documented in the Console API. 



