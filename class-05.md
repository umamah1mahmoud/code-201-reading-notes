# **[ Images, Color, Text ]**
![multimedia](https://img.freepik.com/free-vector/illustration-technology-vector_53876-5319.jpg?size=626&ext=jpg)

**Today we're talking about some multimedia elements. So why don't we start by defining what exatly is "multimedia"..**

**Multimedia** is a form of communication that combines different content forms such as text, audio, images, animations, or video into a single presentation, in contrast to traditional mass media, such as printed material or audio recordings. Popular examples of multimedia include video podcasts, audio slideshows, animated shows, and movies. (According to [wikipedia](https://en.wikipedia.org/wiki/Multimedia))

**Today** however, we're only discussing images and text as multimedia. And colors as a very important element in all multimedia variations.

<hr/>

## **#1 [ Images ]**
#### (Adding Images to Pages, The Right Format, Optimizing Images for The Web)
<br/>

There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.
That besides all the statics and studies of how large is images influence. Humans are visual creatures.

![images](https://www.easel.ly/blog/wp-content/uploads/2014/04/humans-are-visual-learners.gif)
* You will find more on this topic in the sources.

### **A. How to Add Images to Pages?**
The first step of adding images is choosing them on design and logical bases; images should:
* Be relevant.
* Convey information.
* Convey the right mood.
* Be instantly recognisable.
* Fit the color palette.

Now, to our main questio.. How to?
It's needless to say at this point that we need to add a code so, what is it?


    <img src="https://cdn.wallpapersafari.com/23/52/QVj1oK.jpg" alt="An abstarct design" title="Modern geometric abstractive design. In blue and orange." />

The output of the image in this code should be:

![imageExample](https://cdn.wallpapersafari.com/23/52/QVj1oK.jpg)

<br/>

We added an image, what's next? manipulating it of course! and here comes our dear _**CSS**_ . Either inline, internal or extrnal.
However, there are some simple specifications that can be added to the image code after the source. Like the next example of controlling its dimensions:

    <img src="https://cdn.wallpapersafari.com/23/52/QVj1oK.jpg" alt="An abstarct design" width="600" height="450" />

There are of course much more codes to control using images, either manipulating them or their position in a page. Those I'll leave for you to dig in.

In the beginning we mentioned some design and logic related rules to choose images, now to technical rules:

* Save images in the right format.
* Save images at the right size.
* Use the correct resolution.

### **Tools to edit & save images:**
There are many online and offline tools; absolutely the king on this throne is Adobe Photoshop. And the rest of the royal family of The Adobe's. Well, there are of course many other important tools. Even phone apps at some point. Feel free to search and find more of those tools.

Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

<hr/>

## **#2 [ Color ]**
#### (How to specify colors, Color terminology and contrast, Background color)
<br/>

![color](https://i.ytimg.com/vi/_2LLXnUdUIc/maxresdefault.jpg)

<br/>

Understanding  Color: Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.

Color picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B.

Now we will get introduced to two very basic, simple and important terms..
### **1. Colors properties:**
![colorProp](https://i.pinimg.com/originals/8c/ff/75/8cff7547c044f5522c700987a3c3156e.jpg)

<br/>

### **2. Colors Names in CSS color codes:**
![colorsNmaes](https://tutorial.techaltum.com/images/css-colors.jpg)

### **CSS3: HSL Colors:** 
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.

CSS3: HSL & HSLA; <br/>
The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for hue, saturation, lightness and alpha.<br> Code example:


    body {
    background-color: #C8C8C8;
    background-color: hsl(0,0%,78%);}
    p {
    background-color: #ffffff;
    background-color: hsla(0,100%,100%,0.5);}
* This code is taken derictly from the source.

<hr/>

## **#3 [ Text ]**
#### (Size and typeface of text, Bold, italics, capitals, underlines and Spacing between lines, words, and letters)
<br/>

![text](https://lh3.googleusercontent.com/proxy/kqr6o3wpIqujhXaS3b9sAwjIDJDadZUm6Hx6uL3TdcZSUfz6Ro9w8pI1F3j1wYvGp4nB1XOM1L84_OnE)

The properties that allow you to control the appearance of text can be split into two groups:

* Those that directly affect the font and its appearance
(including the typeface, whether it is regular, bold or italic, and the size of the text).

* Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters).

<br/>

### **Choosing a Typeface for your Website:**
When choosing a typeface, it is important to understand that a browser will usually only display it if it's installed on that user's computer. <br/> For Example, If you design on a Mac, it is important to check what the typefaces look like on a PC because PCs can render type less smoothly. But if you design on a PC, then it should look fine on a Mac.

*Now let's talk some tips and tricks..*

### **A. Size of Type:**
The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. Most common are in the next example showing their names and their output:

![sizeText](https://i.stack.imgur.com/wIts2.gif)

* You may have noticed that programs such as
Word, Photoshop and InDesign offer the same
sizes of text. This is because they are set
according to a scale or ratio that
was developed by European
typographers in the sixteenth
century.

* Recently, some web designers have started to leave the body text at the default size of 16 pixels and adjust the other font sizes using a scale that keeps the relative proportions of this one.

### **B. Bold, Italics, Capitals and Underline:**

![bItUnd](https://d33v4339jhl8k0.cloudfront.net/docs/assets/588089eddd8c8e484b24e90a/images/5bb4b8a62c7d3a04dd5b3d52/file-GCRiCH0OJW.png)

There isn't much to explain about those famous tools, so let's get into the real thing.. Coding!

1. **Bold**:

       p.thick {
       font-weight: bold;
       }

2. *Italic*:

        p.a {
        font-style: normal;
        }

3. CAPITALS: (Or to small letters by changing uppercase to lowercase).

        div.a {
        text-transform: uppercase;
        }

4. Underline:

        h3 {
        text-decoration: underline;

### **C. Spacing Between Lines:**

1. l e t t e r  S p a c i n g:

        h1 {
        letter-spacing: 3px;
        }

2.  Word  Spacing:

        p {
        word-spacing: 30px;
        }

## Note:
There are of course so many other properties and fun codes, try to search for more and have fun!

<hr/>

## **#4 [ Extra Article: Image Formats ]**
#### (JPEG vs PNG vs GIF — which image format to use and when?)
<br/>

There are hundreds of image formats available each with a specific use case. In this post, we would only be looking at the three most commonly used image formats in websites and mobile applications — JPEG, PNG and GIF.

![imageFormats](https://ignitiondrawing.files.wordpress.com/2018/05/jpg-png-gif.gif?w=379)

* You have a clue now from the previous **GIF** on what differences they have but more explanation will follow..

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

<hr/>

That was all for today's notes. Today I used multiple sources two of which were provided by our instructors and one that I found really helpful in explaining how important images are and more effective. I will list them hoping you'll find them as handy as I found them:

* First with the article I added, [Text vs. Images: Which Content Format is Effective?](https://www.easel.ly/blog/text-vs-images-which-content-format-effective/)

Other sources:

* HTML & CSS Design and Build Websites - By: Jon Ducket.
* [JPEG vs PNG vs GIF — which image format to use and when?](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)