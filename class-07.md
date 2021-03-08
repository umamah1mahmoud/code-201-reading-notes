# **[ Domain Modeling, HTML Tables; JS Constructor Functions ]**
![HtmlCss](https://miro.medium.com/max/675/1*dqLV7KjUtg57JPBCilqxSQ.jpeg)

<hr/>

## **#1 [ Domain Modeling ]**
#### (Domain modeling is the process of creating a conceptual model in code for a specific problem. )
<br/>

**Define a constructor and initialize properties:** <br/>
To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an object.

![table](https://i.stack.imgur.com/31MFN.png)

This is object-oriented programming in JavaScript at its most fundamental level.

The new keyword instantiates (i.e. creates) an object.
The constructor function initializes properties inside that object using the this variable.
The object is stored in a variable for later use.

### **Here's some tips to follow when building your own domain models.**

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

<hr/>

## **#2 [ HTML Tables ]**
#### (How to create tables, What information suits tables, How to represent complex data in tables).

<br/>
A table represents information in a grid format. There are several types of information that need to be displayed in a grid or table.

<br/>

### **How to create tables:**

    <table style="width:100%">
    <tr>
        <th>tablerow1</th>
        <th>tablerow2</th>
        <th>tablerow3</th>
    </tr>
    <tr>
        <td>tabledata1</td>
        <td>tabledata2</td>
        <td>tabledata3</td>
    </tr>
    <tr>
        <td>tabledataA</td>
        <td>tabledataB</td>
        <td>tabledataC</td>
    </tr>
    </table>

* This code should come out like this:

<table style="width:100%">
    <tr>
        <th>tablerow1</th>
        <th>tablerow2</th>
        <th>tablerow3</th>
    </tr>
    <tr>
        <td>tabledata1</td>
        <td>tabledata2</td>
        <td>tabledata3</td>
    </tr>
    <tr>
        <td>tabledataA</td>
        <td>tabledataB</td>
        <td>tabledataC</td>
    </tr>
    </table>

<br/>

* For long tables you can split the table into a < thead>,
< tbody>, and <t foot>.

<hr/>

## **#3 [ JS Constructor Functions ]**
#### (The new keyboard and the object constructor create a blank object. You can then add properties and methods to the object).

![object](https://fireship.io/courses/javascript/img/js-object-props.png)

* You can use this syntax to add properties and methods to an object.

<br/>

### **Arrays as objects:**
    var cars = ["Saab", "Volvo", "BMW"];
    document.getElementById("demo").innerHTML = cars[0];

### **Built in objects:**
Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages. 

**Example:** The window object:

**Some Window Object Properties:**

| Property |	  Description              |
| -------- |----------------|
closed |	Returns a Boolean value indicating whether a window has been closed or not
console	| Returns a reference to the Console object, which provides methods for logging information to the browser's console (See Console object)
defaultStatus |	Sets or returns the default text in the statusbar of a window

<br/>

**Some Window Object Methods**

|Method |	Description|
| -------- |----------------|
alert() |	Displays an alert box with a message and an OK button|
atob() |	Decodes a base-64 encoded string|
blur() |	Removes focus from the current window|

### **Data types revisited:**
(Simple and complex types);

* Simple types are:
1. String
2. Number
3. Boolean
4. Undefined (a variable that has been declared, but
no value has been assigned to it yet)
5. Null

* Complex type: Objects


### **Global Objects**
A global object is an object that always exists in the global scope.

In JavaScript, there's always a global object defined. In a web browser, when scripts create global variables defined with the var keyword, they're created as members of the global object.

For example, Date and time objects.

<hr>
**Sources:**

* HTML & CSS Design and Build Websites - By: Jon Ducket
* Javascript and Jquery Interactive - By: Jon Ducket
* [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)