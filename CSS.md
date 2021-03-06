Making everything look pretty with CSS
========

The reference material can be found [here](https://github.com/OperationSpark/javascript-wiki/wiki/CSS)

#### TODO 1

```css
body {
        background-color: blue;
}
```

* In Cloud9 create a file and name it CSS.html 
* Copy the contents of [this page](https://raw.githubusercontent.com/OperationSpark/teacher-training-curriculum/master/CSS.html) into that file and save it.
* Write the code sample you see above in between the `<style>` tags. 
* Choose a different color. 
* Save that and check out your work. You changed the background color! Hoorah! 

Now we'll add some text to the page and style it: 

* Inside the body tags write a header with `<h1>` and paragraph with `<p>`. 
* Go back inside the style tags where you set the background color. Below that set h1 as the selector and make the font size 30 pixels. 
* And below that set p as the selector and choose a color for that text with the color property. 


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

### TODO 2

* Create a div element in CSS.html underneath the paragraph element
* Write some text inside of it
* Go back up to `<style>` and type out the above code inside
* Add a 5th property below padding-left to give the div a background color like you did for the body. Make sure it's a different color than the body.
* Save your work and view it

Notice the amount of space between the words you typed into the div and the edge of the box. 
There's more space on top because you set the number of pixels to 20. And on the left there is no space at all
because you set the padding to 0. 

### TODO 3

* Set some padding to both the h1 and p elements you created. Specifically play around with padding on the left side.
* Save your changes and view them.

### TODO 4

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

What do you see different about that div? It has been pushed further down the page and also to the left. To be more specific it is 50 pixels further down 
the page due to the properties margin-top and margin-left.

### TODO 5

```HTML
<h1>Plain header</h1>
<h1 class="special">Custom header</h1>
<h1>Plain header</h1>
```
We're going to apply a class to an `<h1>` element. 

* Copy the above code into CSS.html. 
* Create a class called **special** in the CSS. 
* Give the class some properties like font size or color. 
* Save your changes and view them. 

The Custom header text is different than the rest because you styled it that way. 