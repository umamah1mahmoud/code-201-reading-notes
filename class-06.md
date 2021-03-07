# **[ Objects, the DOM, and Problem Domain ]**

![objects](https://s3-us-west-2.amazonaws.com/cleverbeagle-uploads/What-is-a-JavaScript-object.png)

**Just as you guessed. Today we're talking Javascript.. Finishing today's notes with an extra article. Grab your warm cup of coffee and let's get started!**

<hr/>

## **#1 [Objects ]**
#### (Objects group together a set of variables and functions to create a model  of a something you would recognize from the real world. In an object, variables and functions take on new names.)
<br/>

* **Creating** an object: There are several ways to creat an object. However literal notation comes out as the easiest and most popular. Foloows an example of it from [w3schools.com](https://www.w3schools.com/js/js_objects.asp):

      var car = "Fiat";
      var car = {type:"Fiat", model:"500", color:"white"};

Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named car. The values are written as name:value pairs (name and value separated by a colon).

And here's an exercise on objects for you from the same website: [w3scools exercise](https://www.w3schools.com/js/exercise_js.asp?filename=exercise_js_objects1)

<hr/>

## **#2 [Document Object Model ]**
#### (The Document Object Model (DOM) specifies  how browsers should create a model of an HTML  page and how JavaScript can access and update the contents of a web page while it is in the browser window.)

<br/>

The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. 
It is implemented by all major browser makers, and covers two primary areas:

<br/>

### **1. The DOM tree: Making a model of the HTML page.**
The HTML web page that gets loaded on the browser is represented using the 'document' object of BOM model.

This object considers the web page as a tree which is referred to as Document Object Model ( DOM ). Each node of this tree represents HTML elements in the page as 'element' object and its attributes as properties of the 'element' object.

**The body of HTML page:**

![html-page](https://www.bookofnetwork.com/images/javascript-images/domhtmlcode.jpg)

**The DOM tree**:

![DOM-tree](https://www.bookofnetwork.com/images/javascript-images/domstructure.jpg)

<br/>

### **2. Accessing and changing the HTML page.**
To manipulate the style of an HTML element we can use the following property of 'element' object given by DOM API:

![changing-HTML](https://www.bookofnetwork.com/images/javascript-images/JSSlide20209Mar171438.png)

<hr/>

## **#3 [The Problem Domain ]**
#### (Understanding The Problem Domain Is The Hardest Part Of Programming..)

Have you ever tried solving a jigsaw puzzle? If you have any idea of it. You know that the harder ones are those that with the more unclear final picture. For example..

![puzzle](https://d2qpatdq99d39w.cloudfront.net/wp-content/uploads/2020/05/13111257/hard-puzzles-1.jpg)

In this puzzle, you can't exactly see "the whole picture" while trying to finish it. The small tiny parts might make some sense, but overall it's hard to imagine. Now imagine having such as blurry vesion but with coding! Exactly.. It is indeed way hrder.

And that is what made the article writer **John Sonmez** assign it as the hardest part of programming among other parts.

So, **What can be done about it?** The writer suggests two main methods which are;
1. Make the problem domain easier.
2. Get better at understanding the problem domain.

Better understanding and careful analyzing for the problem domain not only makes it easier it also makes you feel more certain about the proccess you're doing, all the how's and why's. And with its expected results.

<hr/>

Sources:
* Javascript and Jquery Interactive - By: Jon Ducket
* [Understanding The Problem Domain Is The Hardest Part Of Programming; An article By John Sonmez](https://dzone.com/articles/understanding-problem-domain)