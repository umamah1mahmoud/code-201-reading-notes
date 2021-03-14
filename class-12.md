# **[ Chart.js, Canvas ]**
![multimedia](https://support.infogram.com/hc/article_attachments/360022434134/tabs.gif)

<hr>

## **#1 [ Charts.js ]**
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element.

### **Setting Up**<br>
At first you'll need to download Chart.js. Then create a new html page and import the script.

### **What can you do with charts?**<br>
- Drawing a line chart.
- Drawing a pie chart.
- Drawing a bar chart.

The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options to do.

* You can use this guiding link to download it and use the sources in it: [Chart.js](https://www.chartjs.org/docs/latest/)

<hr>

## **#2 [ < Canvas > ]**

### **Intro:**

    <canvas id="tutorial" width="150" height="150"></canvas>

At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. Plus that it needs a closing tag.

### **Drawing shapes:**
**The Grid:** Before we can start drawing, we need to talk about the canvas grid or coordinate space. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin.


Using < canvas> allows you to draw many things like:<br>
1. Rectangles.
2. Paths.
3. Triangles.
4. Moving Pen.
5. Lines.
6. Arcs.

- You can also make a combination of those above and more.

### **Applying styles and colors:**

Now we will explore the canvas options we have to make canvas drawings a little more attractive!

What can we style in canvas drawings?<br>
1. Colors.
2. Ttransparency.
3. Lines styles.
4. Gradients.
5. Patterns.
6. Shadows.

* You will find more details about the mentioned points in the source link at the end of this class notes.

### **Drawing text:**
We will now have a look at how to draw text onto the canvas..

The canvas rendering context provides two methods to render text:
* fillText:

        fillText(text, x, y [, maxWidth])

* strokeText:

        strokeText(text, x, y [, maxWidth])

**Styling text**
You can style it just as you can style any other text; that said it means you can easily control the following:

1. Font.
2. Text align.
3. Text baseline.
4. Direction.
<hr>

Sources:
* [Easily Create Stunning Animated Charts With Chart.js by: Sara Vieira](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
* [Chart.js](https://www.chartjs.org/docs/latest/)
* [Basic usage of canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
* [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
* [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
* [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)