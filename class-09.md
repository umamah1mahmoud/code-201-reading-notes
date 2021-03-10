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

### **2.Adding borders and backgrounds to tables**