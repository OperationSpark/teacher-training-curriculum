{"filter":false,"title":"CSS.md","tooltip":"/javascript-wiki.wiki/CSS.md","undoManager":{"mark":31,"position":31,"stack":[[{"group":"doc","deltas":[{"start":{"row":0,"column":0},"end":{"row":178,"column":0},"action":"insert","lines":["Making everything look pretty with CSS","========","","","##### Cascading Style Sheets, or CSS, is what give websites style. Without CSS, the internet would be a very bland place. ","","Facebook with CSS:","","<img src=\"img/facebook-with-css.png\">","","Facebook without CSS: ","","<img src=\"img/facebook-without-css.png\">","","Here are just a few things you can do with CSS: ","","* Choose colors of everything on the page like the background, font, or main menu.","* Set the size of any element such as font size, width of the entire site, or an image","* Create borders or drop shadows around whole sites, images, and menus","* Change the state of items when hovering over them","","To make CSS work you select an HTML element and assign various properties to it. ","","One of the first things you might want to do on any site, if you're not satisfied with white, is to change the background color.","","```css","body {","        background-color: blue;","}","```","","We're selecting the body element, which encompasses the entire page, and setting the background color to blue. Body is a **selector** and the background-color is a **property**.","Look over the formatting in that code. ","","We have: ","","* The selector ","* A curly bracket","* The property ","* A colon","* The value of the property","* A semicolon","* A curly bracket","","The spacing and indenting doesn't matter but it's best to format it like that for readability. Note that als","","#### Step 1","","Open Lesson4.html and write the code sample you see above in between the `<style>` tags. Choose a different color. Save that and check out your work.","You changed the background color! Hoorah! ","","Now we'll add some text to the page and style it: ","","* Inside the body tags write a header with `<h1>` and paragraph with `<p>`. ","* Now go up to the place where you set the background color, inside the style tags, and below that set h1 as the selector and make the font size 30 pixels. ","* Below that set p as the selector and choose a color for that text with the color property. ","","","It should look something like this:","","```css","<style type=\"text/css\">","","    body {","            background-color: blue;","    }","    ","    h1 {","            font-size: 30px;","    }","    ","    p  {","            color: red;","    }","    ","</style>","```","Save your changes and view them. Take note that the background-color property is used for backgrounds (not surprisingly) but the","color property is only used to change the color of text. Your heading is still black because you only set the color on the p tag. ","","We're using **pixels** to set the font size in the above code. Pixels are one of several units of measurement you can use to set length. ","You can use it to set many values such as font-size, padding, and margin. ","","### Padding ","Now we're going to start playing with padding. **Padding** is the amount space around content that is inside of an element.  You can set padding on all four sides of an element.","","Here's an example of padding around a div:","","```HTML ","div {","        padding-top: 20px;","        padding-right: 10px;","        padding-bottom: 5px;","        padding-left: 0;","    }","```","Remember that the div is the selector and there are four properties which apply to padding.","","### Step 2","","* Create a div element in Lesson4.html underneath the paragraph element","* Write some text inside of it","* Go back up to `<style>` and type out the above code inside","* Add a 5th property below padding-left to give the div a background color like you did for the body. Make sure it's a different color than the body.","* Save your work and view it","","Notice the amount of space between the words you typed into the div and the edge of the box. ","There's more space on top because you set the number of pixels to 20. And on the left there is no space at all","because you set the padding to 0. ","","### Step 3","","* Set some padding to both the h1 and p elements you created. Specifically play around with padding on the left side.","* Save your changes and view them.","","### Margins","A **margin** is the amount of space outside of an element. You can set it on all four side like padding.","","### Step 4","","* On the div selector in your CSS add some properties above the padding to set margins.","* Set the margin-top to 50 pixels and the margin-left to 20 pixels. Don't worry about right or bottom now.","* Save your work and view it. ","","The code should look like this: ","","```CSS","div {","        margin-top: 50px;","        margin-left: 20px;","        padding-top: 20px;","        padding-right: 10px;","        padding-bottom: 5px;","        padding-left: 0;","        background-color: green;","    }","```","","What do you see different about that div? It has been pushed further down the page and also to the left. To be more specific it is 50 pixels further down ","the page due to the properties margin-top and margin-left.","","## Classes and IDs","","When you want to get more specific than all of the HTML elements across a site you use classes and IDs to do that. You will often want to apply styling to","only certain HTML elements rather than all of them. In the above code examples we're selecting the `<h1>` and `<p>` elements. The CSS styling you applied","will change the look of all of the `<h1>` and `<p>` elements across the site. ","","","Classes in CSS are created with a period and the class name: ","","```CSS",".class-name {","    font-size: 20px;","}","```","","### Step 5","","```HTML","<h1>Plain header</h1>","<h1 class=\"special\">Custom header</h1>","<h1>Plain header</h1>","```","We're going to apply a class to an `<h1>` element. ","","* Copy the above code into Lesson4.html. ","* Create a class called **special** in the CSS. ","* Give the class some properties like font size or color. ","* Save your changes and view them. ","","The Customer header text is different than the rest because you styled it that way. ","","","","","","","",""]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":0},"end":{"row":48,"column":1},"action":"insert","lines":["*"]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":1},"end":{"row":48,"column":2},"action":"insert","lines":[" "]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":23},"end":{"row":48,"column":24},"action":"remove","lines":[" "]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":22},"end":{"row":48,"column":23},"action":"remove","lines":["d"]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":21},"end":{"row":48,"column":22},"action":"remove","lines":["n"]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":20},"end":{"row":48,"column":21},"action":"remove","lines":["a"]}]}],[{"group":"doc","deltas":[{"start":{"row":48,"column":20},"end":{"row":49,"column":0},"action":"insert","lines":["",""]},{"start":{"row":49,"column":0},"end":{"row":49,"column":2},"action":"insert","lines":["* "]}]}],[{"group":"doc","deltas":[{"start":{"row":49,"column":2},"end":{"row":49,"column":3},"action":"remove","lines":["w"]}]}],[{"group":"doc","deltas":[{"start":{"row":49,"column":2},"end":{"row":49,"column":3},"action":"insert","lines":["W"]}]}],[{"group":"doc","deltas":[{"start":{"row":49,"column":69},"end":{"row":50,"column":0},"action":"insert","lines":["",""]},{"start":{"row":50,"column":0},"end":{"row":50,"column":2},"action":"insert","lines":["* "]}]}],[{"group":"doc","deltas":[{"start":{"row":50,"column":28},"end":{"row":51,"column":0},"action":"insert","lines":["",""]},{"start":{"row":51,"column":0},"end":{"row":51,"column":2},"action":"insert","lines":["* "]}]}],[{"group":"doc","deltas":[{"start":{"row":51,"column":36},"end":{"row":52,"column":0},"action":"remove","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":51,"column":36},"end":{"row":51,"column":37},"action":"insert","lines":[" "]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":0},"end":{"row":175,"column":99},"action":"insert","lines":["https://docs.google.com/forms/d/11lfHi2HZAymtWn11RFFtYkSo8QVFWkDydXVUngpaD40/viewform?usp=send_form"]}]}],[{"group":"doc","deltas":[{"start":{"row":174,"column":0},"end":{"row":175,"column":0},"action":"insert","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":0},"end":{"row":176,"column":0},"action":"insert","lines":["<a href=\"https://docs.google.com/forms/d/1r-giSxysqmMqO36c9_cSKVPCqRRurtTdF-UoYEouGFM/viewform?usp=send_form\" target=\"_blank\"><img src=\"https://raw.githubusercontent.com/OperationSpark/javascript-wiki/master/images/btn-quiz.png\" alt=\"Take the quiz\"></a>",""]}]}],[{"group":"doc","deltas":[{"start":{"row":177,"column":0},"end":{"row":178,"column":0},"action":"remove","lines":["https://docs.google.com/forms/d/11lfHi2HZAymtWn11RFFtYkSo8QVFWkDydXVUngpaD40/viewform?usp=send_form",""]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":9},"end":{"row":175,"column":48},"action":"remove","lines":["https://docs.google.com/forms/d/1r-giSx"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":9},"end":{"row":175,"column":58},"action":"remove","lines":["ysqmMqO36c9_cSKVPCqRRurtTdF-UoYEouGFM/viewform?us"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":19},"end":{"row":175,"column":20},"action":"remove","lines":["m"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":18},"end":{"row":175,"column":19},"action":"remove","lines":["r"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":17},"end":{"row":175,"column":18},"action":"remove","lines":["o"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":16},"end":{"row":175,"column":17},"action":"remove","lines":["f"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":15},"end":{"row":175,"column":16},"action":"remove","lines":["_"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":14},"end":{"row":175,"column":15},"action":"remove","lines":["d"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":13},"end":{"row":175,"column":14},"action":"remove","lines":["n"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":12},"end":{"row":175,"column":13},"action":"remove","lines":["e"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":11},"end":{"row":175,"column":12},"action":"remove","lines":["s"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":10},"end":{"row":175,"column":11},"action":"remove","lines":["="]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":9},"end":{"row":175,"column":10},"action":"remove","lines":["p"]}]}],[{"group":"doc","deltas":[{"start":{"row":175,"column":9},"end":{"row":176,"column":0},"action":"insert","lines":["https://docs.google.com/forms/d/11lfHi2HZAymtWn11RFFtYkSo8QVFWkDydXVUngpaD40/viewform?usp=send_form",""]}]}]]},"ace":{"folds":[],"scrolltop":2711.227053642273,"scrollleft":0,"selection":{"start":{"row":172,"column":20},"end":{"row":172,"column":20},"isBackwards":false},"options":{"guessTabSize":true,"useWrapMode":false,"wrapToView":true},"firstLineState":{"row":33,"state":"allowBlock","mode":"ace/mode/markdown"}},"timestamp":1418847039100,"hash":"628543ef4401dcd4928d5bc54f876112f2e1923c"}