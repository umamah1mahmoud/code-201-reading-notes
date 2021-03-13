# **[ Images, Video , Audio and Practical Information ]**
![multimedia](https://newsignature.com/wp-content/uploads/2017/09/media-industry-banner-img.png)

<hr>

## **#1 [ Images ]**
Controlling size and alignment of images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup. You can also use background images.

### **Basic Images Control:**
You can control images through in-line styling, or using id and class through external CSS file.
- Size of images syntax:

        img {
        width: 100px;
        hight: auto;
        }
- Aligning images syntax:

        img {
        display: block;
        float: right;
        margin-left: 150px;
        margin-right: 200px;
        width: 40%;
        }
- Centering images syntax:

        img {
        display: block;
        margin-left: auto;
        margin-right: auto;
        }

### **Background images:**
You can use a background image behind the box created by any element on a page. Background images can appear just once or be repeated across the background of the box.

- Background image syntax:

        body {
        background-image: url ("images/backgroundImage.jpg");
        }

- controlling background image repetition and position:

        body {
        background-image: url ("images/backgroundImage.jpg");
        background-repeat: no-repeat;
        background-position: center top;
        }

- Shorthand: The background property acts like a shorthand for all of the other background properties you have just seen, and also the background-color property.

        body {
        background: #ffffff url("images/backgroundImage.jpg") 
        no-repeat center top;
        }

### **Image rollovers and sprites:**
You can create image rollover effects by moving the 
background position of an image. To reduce the number of images your browser has to 
load, you can create image sprites.

<hr>

## **#2 [ Video & Audio APIs ]**

HTML5 comes with elements for embedding rich media in documents - < video> and < audio> - which in turn come with their own APIs for controlling playback.

![video](https://steemitimages.com/0x0/https://cdn.dribbble.com/users/1310166/screenshots/3991818/illustration-small.gif)

### **In HTML**
- The whole player is wrapped in a < div> element, so it can all be styled as one unit if needed.
- We have four < button>s — play/pause, stop, rewind, and fast forward.

### **In CSS**

Controls:
- We start off with the visibility of the custom controls set to hidden. 
- We give the controls an opacity of 0.5 by default, so that they are less distracting when you are trying to watch the video.

Display and Buttons:
- We use the ::before selector to display the content before each < button> element.
- We use the content property to set the content to be displayed in each case to be equal to the contents of the data-icon attribute. In the case of our play button, data-icon contains a capital "P".

Timer:
- We set the outer .timer < div> to have flex: 5, so it takes up most of the width of the controls bar.
- We also give our inner < div> and < span> the right amount of z-index so that the timer will be displayed on top.

### **Implementing the JavaScript**
- You can improve the efficiency of the code by creating a separate function that runs these lines, then calling that anywhere it is needed, rather than repeating the lines multiple times in the code.

(The steps however are longer than what a short reading can take, don't hesitate to check it out from the sources.)

<hr>

## **#3 [ Practical Information ]**
<br>

![info](https://www.octoboard.com/static/assets/imports/octocat/real-time-business-dashboard-from-octoboard.gif)

Statics and analysis  always help, it might be much work to do.. In this part you'll get to know tools that come handy in such topic. So let's go!

### **1. Search engine optimization (SEO)**
Search engine optimization helps visitors find your 
sites when using search engines.

**On-page techniques:**
In every page of your website there are seven key places where keywords can appear in order to improve its findability:

1. Page title.
2. URL/ web address.
3. Headings.
4. Text.
5. Link text.
6. Image "alt" text.
7. Page description.

<br>

### **2. Using analytics to understand visitors**

**How does it work?**

- Analytics tools such as Google Analytics allow you to 
see how many people visit your site, how they find it, 
and what they do when they get there.

<br>

**How many people are coming to your website?**
<br>The data you can get:

- Visits.
- Unique visits.
- Page views.
- Pages per visit.
- Average time on site.

<br>

**What are your visitors looking at?**
<br>The data you can get:

- Pages.
- Landing pages.
- Top exit pages.
- Bounce rate.

<br>

**Where are your visitors coming from?**
<br>The data you can get:

- Referrers.
- Direct.
- Search Terms.
- And other advanced Features.

<hr/>
<br>

### **3. Finally!! Putting your site on the web**
<br>

![page](https://99designs-blog.imgix.net/blog/wp-content/uploads/2018/09/WHAT-IS-WEB-DESIGN.jpg?auto=format&q=60&fit=max&w=930)

To put your site on the web, you will need to obtain a 
domain name and web hosting.

**Hosted services:**<br>
There are a number of online services for blogging, email 
newsletters, e-commerce and other popular website 
tools (to save you writing them from scratch).

**FTP & third party tools:**<br>
- File Transfer Protocol (FTP) programs allow you to transfer files from your local computer to your web server.

- Third party tools: There are a wide variety of sites that offer services commonly created by web developers 
(to save you having to build them yourself). <br>
Examples: wordpress.com , mailchimp.com , addthis.com

<hr>

Sources:
* HTML & CSS Design and Build Websites - By: Jon Duckett
* [MDN article on audio and video elements](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)