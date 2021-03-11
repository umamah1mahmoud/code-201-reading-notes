# **[  JS Error and Handling Debugging ]**

![debugging](https://cdn.dribbble.com/users/410036/screenshots/3257787/dribbble-glitch.gif)

JavaScript can be hard to learn and everyone makes mistakes when writing it. These notes will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully. 

<hr>

## **#1 [ Understanding JS; execution and scopes ]**

![js](https://miro.medium.com/max/3840/1*820daPdIGJQYgy_wE2QWWg.jpeg)

### **Order of execution**
To find the source of an error, it helps to know how scripts are processed. 
Tasks run in different orders depending on the code. One code may not run if the code before needs to complete, or if the code after is run.


### **Execution context**
The JavaScript interpreter uses the concept of execution contexts:
1. Global; Code in script but not in function.
2. Function Context; Code running inside a function.
3. Eval Context; Code in an internal function.


### **Execution context & hosting**

Each time a script enters a new execution context, there are two phases 
of activity:

1. Prepare:
* The new scope is created 
* Variables, functions, and arguments are created 
* The value of the this keyword is determined 

2. Execute:
* Now it can assign values to variables 
* Reference functions and run their code 
* Execute statements 

### **Understanding Scope**
In the interpreter, each execution context has its own va ri ables object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's variables object.

![scope](https://miro.medium.com/max/3984/1*lskdwh7Th3ug538lVYUscQ.png)

<hr>

## **#2 [ Errors ]**

(If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. )

![error](https://res.cloudinary.com/practicaldev/image/fetch/s--j1mUA5_w--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://ucarecdn.com/e0a5b7b8-33ad-4304-9c1c-0253f97bf48c/)

<br>

### **Error objects**

Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
When an Error object is created, it will contain the following properties:
* name
* messages
* fileNumber
* lineNumber 

There are seven types of built-in error objects in JavaScript:

1. Error
2. Syntax Error
3. Reference Error
4. Type Error
5. Range Error
6. URI Error
7. Eval Error
<hr>

## **#3 [ How to deal with errors? ]**
(Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.)

### **1. Debug the script to fix errors:**

If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

A debugging work flow is about deducting. Where is the problem and what is it. 


### **Using Console:**

In order to do that web browsers such as **Chrome** and **Firefox** developed tools to help developers such as **console**. You can console log part by part of your JS code to know where exactly is the error coming from. You can use the following:

1. console.log()
2. console. info()
3. console.warn()
4. console.error()

### **Breakpoints**

You can simple just pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time. You can do that from the browser.

*WHAT IF* you wanted to use it in your code? using just the **debugger** keyword. When the developer tools are open, this will automatically create a breakpoint. 

### **2. Handling exceptions:**
(If you know your code might fail, use try, catch, and finally. Each one is given its own code block.)

    try { 
       // Try to execute this code 
    } catch (exception) { 
       // If there is an exception, run this code 
    } finally { 
       // This always gets executed 
    }

<hr>

## **#4 [ Throwing Errors ]**

* If you know something might cause a problem for your script, you can 
generate your own errors before the interpreter creates them.

* To create your own error, you use the following line: 

       throw new Error('message'); 

If you are working with data from a third party, you may come across problems such as: 

* JSON that contains a formatting error 
* Numeric data that occasionally has a non-numeric value 
* An error from a remote server 
* A set of information with one missing value

<hr>

### **Debugging Tips:**

Here are a selection of useful tips that might help you when debugging your scripts:

1. Another browser.
2. Search, search and search (and learn how to search).
3. Use validation tools.

### **Common Errors:**
1. Go back to basics.
2. Missed/ extra characters (Which might be just a single space sometimes).
3. Data type issues.

<hr>

That was all for this reading notes. I sincerely hope it was helpful enough. You may find keywords that would help you in your farther research about this very important topic.

Also, don't hesitate checking out my informative source:

* JavaScript and jQuery Interactive - By: Jon Duckett