# **[ HTML Links, Intro to CSS Layout, Layout and JS Functions ]**

In this reading note I'm reading more on those topics. You must've noticed that we're getting deeper in each of (HTML, CSS and JS). And as usual we will be starting with HTML. So grab your warm cup of tea. And let's get started!
<hr/>

![html](https://d25yuvogekh0nj.cloudfront.net/2019/07/How-to-Create-Html-Newsletters-blog-banner-1250x500.png)
## **#1 [ HTML Links ]**
#### (Intro, Creating links between pages, Linking to other sites, Email links)
<br/>

### **1. Intro:**
Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing. The syntax is as follows: 

    <a href ="url">link text</a>

### **2. Creating links between pages:**
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file.

Example: 

    < p>
        < ul >
             <li><a href =" index.html "> Home </a></li>     
             <li><a href="about-us.html">About</a></li>
             <li><a href="movies.html">Movies</a></li>
             <li><a href="contact.html">Contact</a></li>
        </ul>
    </p>

The result: <ul>      <li><a href="index.html">Home</a></li>      <li><a href="about-us.html">About</a></li>      <li><a href="movies.html">Movies</a></li>      <li><a href="contact.html">Contact</a></li>  </ul></p>

### **3. Linking to other sites:**
When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.

### **4. Email links:**
To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

    <a href="mailto:jon@example.org">Email Jon</a>

* Can you expect the result of this code now?

There are other links options such as open in a new window, linking to a specific part of the same page and linking to a specific part of other page. Those I'm leaving to you firing curiosity ;)

* Next, we'll be moving to CSS.
<hr/>

![css](https://www.tutorialrepublic.com/lib/images/css-illustration.png)
## **#2 [ Layout ]**
#### (Controlling the position of elements)
In this chapter we are going to look at how to control where each element sits on a page and how to create attractive page layouts.
<br/>

**Key Concepts in Positioning Elements:** 
1. **Building Blocks:** CSS treats each HTML element as if it is in its own box. This box will either be a block-levelbox or an inline box.

![box](https://codinglead.github.io/images/box-model.png)

2. **Containing Elements:** If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

Now, let's move on to controlling the position of an element..

### **Controlling the position of elements:**

CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the positionproperty in CSS. You can also float elements using the float property.

![pos](https://www.internetingishard.com/html-and-css/advanced-positioning/css-positioning-schemes-790d5b.png)

* And of course, what comes after HTML and CSS? Exactly! To JavaScript of we go..
<hr/>

![js](https://www.tutorialrepublic.com/lib/images/javascript-illustration.png)
## **#3 [ JS Functions ]**
#### (Functions, Methods & Objects)
Browsers require very detailed instructions about what we want them t o do. Therefore, complex scripts can run to hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code. 

**1. Functions:** Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).

![function](https://res.cloudinary.com/practicaldev/image/fetch/s--pClJgvrv--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/mt2jlra7jd5gdgl8up8y.png)

So we wrote the function but how do we actually use it? This is called "Calling" the function, or invoking. (In the last line of the next example).

![invoke](https://pbs.twimg.com/media/D1j5S_wWsAc3lPB.jpg)

<hr/>

### _**EXTRA Article Notes:**_ 

![pair](https://raw.githubusercontent.com/DXHeroes/knowledge-base-content/master/files/pair-programming.svg?sanitize=true)
## **[ 6 Reasons for Pair Programming ]**
`“Coworking is all about community, but I believe the ‘work’ part of coworking should be as attractive as the ‘co’ part.”`

-Jerome Chang, founder of the first coworking space in Southern California

We know what coworking is. So when it comes to programming; pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

### **How does it work?**
#### (The driver and the navigator)
It commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer.

### **But why pair program?**

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

### _**Now, let's move to the "6 Reasons for Pair Programming"!**_

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness

If you found those notes helpful for you and you have some questions or need farther explanation. Please don't hesitate visiting the link of this great article from my sources list.

<hr/>

Sources:
* HTML & CSS Design and Build Websites - By: Jon Ducket
* Javascript and Jquery Interactive - By: Jon Ducket
* [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)