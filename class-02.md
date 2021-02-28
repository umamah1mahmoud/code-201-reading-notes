# **[ Digging in HTML, CSS and JS! ]**

### In this reading note there are four main topics. Two of which concerened with HTML and CSS (Text in HTML and Introducing CSS). The other two will be about Javascript (Basic Javascript instructions and Decisions and Loops).

<_**Naturally, we'll start with HTML and CSS. Here we go!**_>

![htmlCSS](https://miro.medium.com/max/675/1*dqLV7KjUtg57JPBCilqxSQ.jpeg)

<hr/>

## **#1 [Text in HTML]**

**1. Headings and Paragraphs:** When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page. For example the headings tags from h1 to h6 (written as < h1 > TypeYourTextHere </ h1>). The difference between might be visually seen as a decreasing of size.  <blockquote> **But more importantly is the meaning behind this decreasing.** </blockquote> By increasing the number beside the "h" and decreasing its size, we're telling the browser that what's "smaller" is actually less important. h1 would be the main header while h2 a subtitle, h3 another smaller topic title... and so on.

**2. Bold and italic:** They're considered as main text edits known and found in many text editors. Naturally, they'll be included in basic html text editing. So, how do they work?

- **Bold:** By enclosing words in the tags
< b> and < /b> we can make characters appear bold.
- *Italic:* By enclosing words in the tags < i> and < /i> we can make characters appear italic.

**Other text styling tricks:**

- **Line Breaks:** If you wanted to add a line break  between lines inside the middle of a paragraph you can use the line break tag < br/>.
- **Horizontal Rules:** To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the < hr /> tag.

**3. Structural and Semantic Markup:** There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup. <br/> While Structural markup is the elements that you can use to describe both headings and paragraphs.

Examples:
- **Quotations:** There are two elements
commonly used for marking up
quotations: The <  blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the < p> element is still
used inside the < blockquote >
element. (You can see it applied in "1. Headings and Paragraphs:"). </br> The < q> element is used for
shorter quotes that sit within
a paragraph. 

- **Abbreviations and Acronyms:** If you use an abbreviation or an acronym, then the < abbr> element can be used. A title attribute on the opening tag is used to specify the full term.

#### Here's a quick quiz for you! Can you guess how the outcome of this code would look like? (You can also try to write it to see it happenening ;) )
![quiz](https://steemitimages.com/DQmUdMF6FqGiZCCyzTSB9su9bYrWVFRx1SvgezjR5u5wahZ/Example.png)

<hr/>

## **#2 [ Introducing CSS ]**

**1. What CSS does:** So, easilt put CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented. 

**2. How CSS works:**
CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. As shown below:

![css](https://filedn.com/ltOdFv1aqz1YIFhf4gTY8D7/ingus-info/BLOGS/CSS-selectors/css-selectors.jpg)

There are three main ways of applying CSS to HTML: inner, internal and external. 


**3. Rules, properties and values:**
- Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
-  Different types of selectors allow you to target your rules at different elements.
- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

<hr/>

![js](https://stackify.com/wp-content/uploads/2018/10/JavaScript-Tutorials-for-Beginners-881x441.jpg)

## **#3 [ Basic Javascript Instructions ]**
- **Statements:** A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. <br/> JavaScript is case sensitive so userName means
something different to UserName or USERNAME.

* **Comments:** You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. However, they do not appear to the user.
 <br/> In order to use it, just type // before your comment.

 * **Variables:** A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. They can be written in three different ways as follows: <br/> 
 ![var](https://1.bp.blogspot.com/-8UmWFTngfwY/XkVRuoPFfkI/AAAAAAAACmI/93j-FMkA9EYyoRIT1qlJ2sMUbobnWT1UgCLcBGAsYHQ/s1600/javascript_var.png)

 ### **DATA TYPES:**
 This is a simple yet very important section, there are three types of data. We need to understand them so we can use them with variables:

 1. Numeric data type (4,7,1).
 2. String data type (that is any character you can see on your keyboard put between quotation marks as, “Student” “6” “!”).
 3. Boolean data type (It can only have one off two values, true or false).

_**Now**_, Back to variables. There are some important rules to naming variables. I'll count for you part of them. Based on the book _**Javascript and jQuery Interactive - By: Jon Ducket**_:
1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
2. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
3. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age.

* You can go back to the mentioned resource for more takes on this.

### **Operators:**
Expressions rely on things called operators; they allow programmers to create a single value from one or more values. <br/> JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class.

![op.](https://www.miltonmarketing.com/wp-content/uploads/2018/04/jsarithimage029.jpg)

<hr/>

## **#4 [ Decisions and Loops ]**
### **1. Decision Making:**
There are some places in script where decisions are made that determine which lines of code should be ran next. The following chart explains that:

![jsChart](https://www.tutorialspoint.com/javascript/images/decision_making.jpg)

### **2. Comparison Operators: Evaluating Conditions**
You can evaluate a situation by comparing one value in the script to what you expect it might be.

![comp](https://www.miltonmarketing.com/wp-content/uploads/2018/04/javascriptcomparisonoperatorsimage041-1200x482.jpg)

* Structuring Comparison Operators:
Example: <br/>
**if (age < 18) text = "Too young to buy alcohol";**

* Using (And) and (Or) Logical Comparisons:

![andor](https://res.cloudinary.com/practicaldev/image/fetch/s--AaxWL-V---/c_imagga_scale,f_auto,fl_progressive,h_720,q_auto,w_1280/https://cl.ly/7d9cf8370380/Image%25202018-11-15%2520at%25209.59.47%2520AM.png)

<hr/>

#### My dear reader, that was it for today's notes. I know it's getting more in details, maybe more complicated. But it should be easier and more clear by practice. I wish I could be as breif as I could -it's really not as easy as it seems- and as informative as I could. Please do not hesitate taking a look on my resources. As they are two of the most important coding books these days:

* HTML & CSS Design and Build Websites - By: Jon Ducket
* Javascript and Jquery Interactive - By: Jon Ducket



