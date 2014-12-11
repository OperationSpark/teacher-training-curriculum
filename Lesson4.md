Making everything look pretty with CSS
========
Lesson 4 will go over the basics of CSS.

### Cascading Style Sheets, or CSS, is what give websites style. Without CSS, the internet would be a very bland place. 

Facebook with CSS:

<img src="img/facebook-with-css.png">

Facebook without CSS: 

<img src="img/facebook-without-css.png">

Here are just a few things you can do with CSS: 

* Choose colors of everything on the page like the background, font, or main menu.
* Set the size of any element such as font size, width of the entire site, or an image
* Create borders or drop shadows around whole sites, images, and menus
* Change the state of items when hovering over them

To make CSS work you select an HTML element and assign various properties to it. 

One of the first things you might want to do on any site, if you're not satisfied with white, is to change the background color.

```css
body {
        background-color: blue;
}
```

We're selecting the body element, which encompasses the entire page, and setting the background color to blue. Body is a **selector** and the background-color is a **property**.
Look over the formatting in that code. 

We have: 

* The selector 
* A curly bracket
* The property 
* A colon
* The value of the property
* A semicolon
* A curly bracket

The spacing and indenting doesn't matter but it's best to format it like that for readability. Note that als

#### Step 1

Open Lesson4.html and write the code sample you see above in between the `<style>` tags. Choose a different color. Save that and check out your work.
You changed the background color! Hoorah! 

Now we'll add some text to the page and style it: 

* Inside the body tags write a header with `<h1>` and paragraph with `<p>`. 
* Now go up to the place where you set the background color, inside the style tags, and below that set h1 as the selector and make the font size 30 pixels. 
* Below that set p as the selector and choose a color for that text with the color property. 


It should look something like this:

```css
<style type="text/css">

    body {
            background-color: blue;
    }
    
    h1 {
            font-size: 30px;
    }
    
    p  {
            color: red;
    }
    
</style>
```
Save your changes and view them. Take note that the background-color property is used for backgrounds (not surprisingly) but the
color property is only used to change the color of text. Your heading is still black because you only set the color on the p tag. 

### Padding and margins
Now we're going to start playing with padding and margins. **Padding** is the amount space around content that is inside of an element. A **margin** is the amount of space outside of
an element. You can set padding and margins on all four sides of an element.

Here's an example of padding around a div:

```HTML 
div {
        padding-top: 20px;
        padding-right: 10px;
        padding-bottom: 10px;
        padding-left: 20px;
    }
```
Remember that the div is the selector and there are four properties which apply to padding.

### Step 2

* Create a div element in Lesson4.html underneath the paragraph element
* Write some text inside of it
* 





