# **[ HTML Layout ]**
![html example](https://www.ultraedit.com/assets/images/lp/html/html-tag.gif)

If you recalled seeing this image somewhere before. Then you guessed right! and I'm referring to the past reading note from code 102: [Structure web pages with HTML](https://umamah1mahmoud.github.io/reading-notes/HTML).

But in this resding notes I'll give it a little more information. As I'm learing more and more about HTML in general, day after the other.

Now, let's get started!
<hr/>

## **#1 [ Controlling the position of elements]**
#### (Key Concepts in Positioning Elements)
<br/>

![pose](https://blog.froont.com/content/images/2015/01/Z-index_FROONT.gif)

So, just as this image states. Positioning is basically setting the postion between things in relation to each other. In H HTML, it's the positions of its elements. With multiple relations types. Which will be mentioned next..

Note that Browsers display pages in normal (built-in) flow unless you specify relative, absolute, or fixed positioning.

### **Building Blocks:**
CSS treats each HTML element as if it is in its  own box. This box will either be a block-level box or an inline box.

< div> elements are often used as containing elements 
to group together sections of a page. (making each one in a separate box).

**Now**, What if? <br>If one block-level element sits inside another block-level element then the outer box It is  known as the containing or **parent element**.

## **Controlling the Position of Elements:**

CSS has the following positioning schemes that allow you to control the layout of a page:

1. **Static:**

![static](https://blog.froont.com/content/images/2015/01/02-Static-position-FROONT.gif)

<br>

2. **Absolute:**

![absolute](https://blog.froont.com/content/images/2015/01/03-Absolute-position-FROONT.gif)

<br>

3. **Relative:**

![relative](https://blog.froont.com/content/images/2015/01/04-Relative-position-FROONT.gif)

<br>

4. **Fixed:**

![fixed](https://blog.froont.com/content/images/2015/01/05-fixed-position-FROONT.gif)


* For more information, check out the amazing webpage I took those fun and informative images from; [Positioning in web design](https://blog.froont.com/positioning-in-web-design/).

<hr>

## **Floting Elements**

The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

To apply it on an item (text or image), we shall follow the next code in css:

        img  {
        float: right;
        }

This code will set any image in the webpage to float to the right side of the elements it's inside. The next picture shows how it looks like either in left or right:

![float](https://i2.wp.com/css-tricks.com/wp-content/uploads/2021/02/web-text-wrap.png?resize=540%2C270&ssl=1)

* There are some other float commands and options, that I leave for you to check out either on the web or the source I will mention at the end.

<hr>

## **Designing for different sized screens**

You must have wondered before, how comes the same webpage easily adjust and adapt to all those different sized screens. It is an important question of course! And you'll get to know the answer..

### **Basic Keywords:**
1. **Screen Sizes:** The size of a user's screen  affects how big they can open  their windows and how much  of the page they will see.
2. **Screen Resolution:** Resolution refers to the number of dots a screen shows per inch. Some  devices have a higher resolution than desktop computers and most  operating systems allow users to adjust the resolution of their screens. <br>
- It is interesting to note that  the higher the resolution, the  smaller the text appears.
3. **Page Sizes:** Because screen sizes and display resolutions vary so much, web designers often try to create pages of around _**[ 960-1000 pixels ]**_ wide  (since most users will be able to see designs this wide on their screens).

* Remember those quite well. And keep them in your mind..

<br/>

### **Fixed Width Layouts**
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels. 


### **Liquid Layouts**

Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

**So**, what are exactly are their pros and cons? I'll show that to you in the following table:


| Layout Type | Pros  | Cons  |
| -------------- | --------------- | -------------|
| **Fixed Width Layout** | Pixel values are accurate at controlling size and  positioning of elements. | You can end up with big gaps around the edge of a page.
|    |The designer has far greater control over the appearance and position of items on the page than with liquid layouts. | If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read. |
|    |You can control the lengths of lines of text regardless of the size of the user's window. | If a user increases fontsizes, text might not fit into the allotted spaces. |
|    |The size of an image will always remain the same relative to the rest of the page. | The design works best on devices that have a site or resolution similar to that of  desktop or laptop computers.|
| **Liquid Width Layout** | Pages expand to fill the entire browser window so there are no spaces around the page on a large screen. | If you do not control the width of sections of the page then the design can look very different than you intended, with unexpected gaps around certain elements or items squashed together. |
|    | If the user has a small window, the page can contract to fit it without the user having to scroll to the side. | If the user has a wide window, lines of text can become very long, which makes them harder to read. |
|      | The design is tolerant of users setting font sizes larger than the designer intended (because the page can stretch). | If the user has a very narrow window, words may be squashed and you can end up with few words on each line. |

<hr>
**Sources:**

* HTML & CSS Design and Build Websites - By: Jon Ducket
* [Positioning in web design](https://blog.froont.com/positioning-in-web-design/).
