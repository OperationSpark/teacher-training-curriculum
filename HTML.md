HTML 
========

The reference material can be found [here](https://github.com/OperationSpark/javascript-wiki/wiki/HTML-Intro)

## Write your first HTML page

### TODO 1

* Open a workspace in Cloud 9. 
* Create a new file by clicking File > New File in the top left and name it index.html. Open the file by double clicking on it.
* First tell the browser what the page is going to be with the DOCTYPE tag: `<!DOCTYPE HTML>`
* Next you need to start the HTML page itself with the `<HTML>` opening and closing tags.

Whenever we have tags inside of other tags we need to indent them for formatting purposes. The browser actually doesn't care about indentations but it's much easier for humans to 
read and understand if code is formatted properly. Part of that is nesting tags accordingly. 

So now let's add some more tags. 
Start with `<head>`and ensure that the opening and closing tags are indented by using the tab key on the keyboard. 

It should looks something like this:

<img src="http://i.imgur.com/BwZDmP9.png" />

From now on we'll use the term HTML element as opposed to tags. An HTML element consists of the opening and closing tags. The tags collectively are called an element. When an element is mentioned, unless otherwise stated, you're expected to use a beginning and ending tag.
Now add `<title>` inside of the head. Make sure it's indented! We need a title so pick something clever to go in between the title tags.

Like this: 
```html
<title>something clever</title>
```

Now we'll start putting some content on the page with the `<body>` element. Add the body element (after the head element) and ensure that it is indented one tab in like the head element. 
Inside of the body element add an `<h1>` element and put some content in it. Then, on the next line, add a `<p>` element and put some content in there as well. Remember to indent. 

Your HTML should look something like:

```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>My first page</title>
    </head>
    <body>
        <h1>Hello World!</h1>
        <p>This is a paragraph.</p>
    </body>
</html>
```

Now click the Run button with the green arrow next to it at the top of the page. That will start up the web server so you can view your page. 
At the bottom, in the terminal, you can see "Starting Apache httpd, serving "https://...." click that link. 
<img src="https://github.com/OperationSpark/javascript-wiki/blob/master/images/run-terminal.png">


That will open your page inside of Cloud 9's window. 
Go ahead and click the arrow inside the box icon on the right side to open that link up in your browser. 

Depending on your browser you'll see something like:

<img src="http://i.imgur.com/XSNoC6u.png" />

So, nothing crazy yet but you made an HTML page! You can see the title you came up with inside of the head element is up top in the tab title. 
And a big, bold heading thanks to the h1 element with some text underneath inside the p element. Now let's view the code that is generated in the browser.
Right-click on the page and click 'View Source.' You can see the code you wrote right in the browser. 

One awesome thing about the web is that you can view the source code of any HTML page. 

### TODO 2
Take a minute to visit three of your favorite websites and view their code just like you did for your own page.
The HTML on those sites will most likely look quite complicated compared to what you just created. You can still see the basic structure though. Peruse through the code to find the same tags you just used.
If you can't find them just press cmd + F on Mac or ctrl + F on Windows and search for html, head, title, and body. 

## Divs

A `<div>` is something that lets you create your own block elements in HTML. Divs are used when other HTML elements aren't suitable for a certain purpose. 
For instance when you're creating header text you would use `<h1>`, `<h2>`, etc. or when you're making a paragraph you use the `<p>` element. There will be 
times when you want to create something on a page and will end up using a div to make it. Most of the time you'll be using CSS to style that div in some way. We'll 
work on that in a future lesson.

### TODO 3
* Create a `<div>` element with opening and closing div tags. 
* Put some text inside the div. 
* Now put another div inside of the first div. Make sure it's indented properly!
* Save your page and view it.

```HTML
<div>
    Here's some text.
        <div></div>
</div>
```

The second div is present but you don't see it because you didn't put anything inside of it. You'll become familiar with nesting divs in later lessons.

<a href="https://docs.google.com/forms/d/1XrMSTU5s7BAAWdwz5OY-Ec7POjGo4_W7sf7mMmfPa40/viewform?usp=send_form" target="_blank"><img src="https://raw.githubusercontent.com/OperationSpark/javascript-wiki/master/images/btn-quiz.png" alt="Take the quiz"></a>



## References

[W3Schools HTML](http://www.w3schools.com/html/html_intro.asp)

