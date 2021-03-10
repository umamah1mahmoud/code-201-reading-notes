# **[ Forms and Events ]**
![forms](https://s3-ap-southeast-2.amazonaws.com/agentcis-wp/wp-content/uploads/20190219051021/lead-form-illustration.png)

Today we dig in all the three together (HTML, CSS and JS), so get ready.. and here we go.

<hr>

## **#1 [ Forms in HTML ]**
#### (What are forms? Why? And how?)..

* Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.
* The best known form on the web is probably 
the search box that sits right in the middle of 
Google's homepage.

Now, we'll move to how, and that you will know by the end of this section..

### **How to collect info from users?**
There are several types of form controls that 
you can use to collect information from visitors 
to your site as follows..


![forms](https://slideplayer.com/slide/13519692/82/images/4/FORM+CONTROLS+Explain%3A+how+there+are+different+types+of+form+control.jpg)


### **Next, how forms work?**
1. A user fills in a form and then presses a button 
to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language. It may also store the information in a database.

* Important note: You should never change the name of a form control in a page unless you know that the code on the server will understand this new value.

### **The code:** As our biggest concern right now..

Here's a quick example of a code and it's outcome:

![form code](https://www.htmlgoodies.com/img/2010/06/HTML-Forms-From-Basics-to-Style-Layouts-Figure2.gif)

This was an example of **Text Input** type of forms, there are many other types such as: text area, radio button, checkbox, multiple select box, etc.

### **New HTML5 form controls:**
A new form elements introduced by HTML5 which make it easier for visitors to fill in forms like: Date input, email and url input and search input.

<hr/>

## **#2 [ Lists, Tables and Forms ]**
There are several CSS properties that 
were created to work with specific types 
of HTML elements, such as lists, tables, 
and forms. So, today we'll talk about:

(Specifying bullet point styles, Adding borders and backgrounds to tables, Changing the appearance of form elements)

### **1.Specifying bullet point styles**
There are two main types of it:
1. List-style-type: You can basically choose any keyboard character (named as **values**) as you **marker**, from letters and numbers to points, circles or stars. <br>
It can be used on < ol> , < ul> and < li> elements.

2. List-style-image: In this case you can choose an image as your list items **marker**. But you can only use it on < ul> and < li> elements.

**Positioning the makrker** <br>
list-style-position; Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points. 

It can take two values: 
* outside
* inside

        ul.b {
        list-style-position: inside;
        }

* Now, I suppose you can guess how will that list look like.. Try and guess ;)


* As with several of the other CSS properties, lists comes also with a list shorthand written in css as **list-style.**

<br>

### **2.Adding borders and backgrounds to tables**

![tables](https://xeroxbus.com.au/wp-content/uploads/2019/02/account-black-and-white-business-209137.jpg)

#### Such an unwelcoming image right? Well, imagine if all tables would only look like that.. That's where CSS comes to save ourlives. How's that? let's figure out..


**What are tables properties?**

- Padding
- Align numerals
- Borders on empty cells
- Gaps between cells

And much more hacks that you can search for and have fun with..

<br/>

### **3.Changing the appearance of form elements**
(Styling forms)

Forms can be such a drag for the most of us, so making a successful form needs to put more effort on the user interface, more welcoming and encouraging to participate.

I talked earlier in this notes about forms and how to make them in HTML. Now we'll talk about taking them to the next level using CSS.

* Some common CSS properties used with user input are: font-size , color , background-color and others.

* Styling submit buttons; color, text-shadow, border-bottom.

* Cursor styles; The cursor property allows you to control the type of mouse cursor that should be displayed to users.

### Web Developer Toolbar:

This helpful extension for Firefox and Chrome provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML.

It shows you: Outline, Structure and CSS styles.

<hr/>

## **#3 [ Events ]**

![js](https://miro.medium.com/max/1400/0*sN7Gh-sRDm_o678f.gif)

#### Here's to a new big JavaScript topic, so get seriously ready. And let's go!

W hen you browse the web, your browser registers different types of events. It's the browser's way of saying,"Hey, this just happened." Your script can then respond to these events. 

The proccess basically goes like: (Interactions creat events, Events trigger code, Code responds to users). When events are **raised** they **trigger** a function or script.

### **1. Interactions create events:**

There are three main types of events that are based on the type of input:
* UI: Occur when a user interacts with the browser's user interface (UI) rather than the web page.
* Keyboard: Occur when a user interacts with the keyboard.
* Mouse: Occur when a user interacts with a mouse. trackpad, or even **touchscreen**. 

### **2. How events trigger JS code?**
There are three steps for it, which are:
1. Select element.
2. Specify element.
3. Call code.

And, there are three **types** to bind an event to an element: (not to mix them with the steps)
* **HTML even handlers:** (NOT SUGGESTED to use at all! just a mention so you can recognize them)
* **Traditional DOM event handlers:** (All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.)
* **DOM level 2 event listeners:** (Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers. )

### **Event Flow:**
![flow](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events/bubbling-capturing.png)

**What is it?** HTML elements nest inside other elements. If you hover or click on a link, you will also be hovering and clicking on its parent elements.

**Why it matters?** The flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendent elements.


### **2. Code respond to users**
There are different types of events you can respond to:

* The W3C DOM specification: (The most commonly used)
* The HTMLS specification 
* In Browser Object Models 

_**Please note that: Events is a huge topic, that some simple reading notes cannot fully cover, to know more about it you must check out the sources or do further search**_

Sources:
* HTML & CSS Design and Build Websites - By: Jon Duckett
* Javascript and Jquery Interactive - By: Jon Duckett


