Making everything look pretty with CSS
========
Lesson 4 will go over the basics of CSS.

#### Cascading Style Sheets, or CSS, is what give websites style. Without CSS, the internet would be a very bland place. 

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

We're using **pixels** to set the font size in the above code. Pixels are one of several units of measurement you can use to set length. 
You can use it to set many values such as font-size, padding, and margin. 

### Padding 
Now we're going to start playing with padding. **Padding** is the amount space around content that is inside of an element.  You can set padding on all four sides of an element.

Here's an example of padding around a div:

```HTML 
div {
        padding-top: 20px;
        padding-right: 10px;
        padding-bottom: 5px;
        padding-left: 0;
    }
```
Remember that the div is the selector and there are four properties which apply to padding.

### Step 2

* Create a div element in Lesson4.html underneath the paragraph element
* Write some text inside of it
* Go back up to <style> and type out the above code inside
* Add a 5th property below padding-left to give the div a background color like you did for the body. Make sure it's a different color than what you
  set for body.
* Save your work and view it

Notice the amount of space between the words you typed into the div and the edge of the box. 
There's more space on top because you set the number of pixels to 20. And on the left there is no space at all
because you set the padding to 0. 

### Step 3

* Set some padding to both the h1 and p elements you created. Specifically play around with padding on the left side.
* Save your changes and view them.

### Margins
A **margin** is the amount of space outside of an element. You can set it on all four side like padding.

### Step 4

* On the div selector in your CSS add some properties above the padding to set margins.
* Set the margin-top to 50 pixels and the margin-left to 20 pixels. Don't worry about right or bottom now.
* Save your work and view it. 

The code should look like this: 

```CSS
div {
        margin-top: 50px;
        margin-left: 20px;
        padding-top: 20px;
        padding-right: 10px;
        padding-bottom: 5px;
        padding-left: 0;
        background-color: green;
    }
```

What do you see different about that div? It has been pushed further down the page and also to the left!

## Classes and IDs






