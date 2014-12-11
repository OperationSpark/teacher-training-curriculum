HTML
=====

## Links, images, lists, and tables

We're going to learn some more HTML elements in the following lesson. There are [many HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
out there but you'll mostly use just a portion of them. 

### Links
A link, also known as a hyperlink, is text, an image, or other element that when clicked on brings a user to another page. That page can be within the same 
site or to another site. Links consist of three main parts: the `<a>` element, the content that you click on that makes up the links, and the URL. 
A URL, or uniform resource locator, is a web address. `http://www.google.com` is a URL. When you type a web address into the browser to visit a website you 
are typing a URL. URLs are defined with the href attribute which you can see in use below.

In HTML:

`<a href="http://www.google.com">This is a link to Google</a>`

Actual link:

<a href="http://www.google.com">This is a link to Google</a>

#### Step 1

Open Lesson3.html, create an HTML page, and create a text link to Facebook. Save the page and view your link.

**Two types of URLs:**

Absolute URLs use the full web address such as `http://www.example.com/path/to/file` and are used when linking to external websites.

Relative URLs use just the path to a page or file and omit the first part such as `path/to/file`. Relative URLs are used to link to other pages
within your website. There is no need to include the full path to your website in a link that is to another part of your website because
you're already on it. 

**Default link behavior**

As you're most likely familiar with, links do a few things to make themselves stand out so you know to click on them. 
By default browser make:

Links are blue and underlined in their normal state

<img src="http://i.imgur.com/erDxSVx.png" />

When hovered over the cursor becomes a hand  

<img src="http://i.imgur.com/3qMNw9D.png" />

When you've visited a link it will become purple. You can change the way links look and act with something called CSS. We'll get to that soon.

### Images
The image element in HTML is one of the few with no closing tag because there is nothing to wrap tags around. 

`<img src="http://i.imgur.com/58eyAmw.jpg" alt="Llama photo">`

<img src="http://i.imgur.com/58eyAmw.jpg" alt="Llama photo">

There are two atriibutes here: src and alt. src is the source of the image which comes in the form of a UR. The alt attribute is what will be displayed if for some reason the 
image isn't available or someone is using a screen reader. Notice the img tag uses just img rather than the full work image.

#### Step 2 
Create an image with HTML

* In Lesson3.html create an image with HTML. 
* Find an image you like on Wikipedia. 
* Right click on the image and click "Copy Image URL" to get the URL. 
* Save the file and view your image. 

#### Step 3 
Create an image link with HTML

* Create a link like you did in Step 1
* Instead of putting text inside that link, insert an image like the one you made in Step 2
* Save the file and click on your image link!

### Lists
HTML lists are found all over the web. There's one directly above in Step 3 They're most often accompanied by bullet points. There are two types of lists: unordered and ordered.

Unordered simply means the list will use bullet points. Ordered means it will display numbers automatically. Ordered lists use the `<ol>` element while 
unordered lists use the `<ul>` element. Unordered lists are used much more often. Both types of lists use the same element to define items which is a list
item or `<li>` element.

Unordered list:

```html
<ul>
    <li>Orange</li>
    <li>Apple</li>
    <li>Banana</li>
</ul>
```

<ul>
    <li>Orange</li>
    <li>Apple</li>
    <li>Banana</li>
</ul>

Ordered list:

```html
<ol>
    <li>Orange</li>
    <li>Apple</li>
    <li>Banana</li>
</ol>
```

<ol>
    <li>Orange</li>
    <li>Apple</li>
    <li>Banana</li>
</ol>

### Tables
Tables are as old as the web, and prior to the advancement of CSS, were used to handle a lot of formatting and alignment on websites. Today tables
are mostly used to display what they should be...tabular data. 

Tables have three main elements:

* `<table>` defines the table itself
* `<tr>` defines a row (remember the r for table row)
* `<td>` defines a cell (td means tabular data)

```html
<table border="1" cellpadding="10">
    <tr>
        <td>Type of fruit</td>
        <td>Number of pieces</td>
    </tr>
    <tr>
        <td>Orange</td>
        <td>4</td>
    </tr>
    <tr>
        <td>Apple</td>
        <td>7</td>
    </tr>
    <tr>
        <td>Berries</td>
        <td>3</td>
    </tr>
</table>

```

<table border="1" cellpadding="10">
    <tr>
        <td>Type of fruit</td>
        <td>Number of pieces</td>
    </tr>
    <tr>
        <td>Orange</td>
        <td>4</td>
    </tr>
    <tr>
        <td>Apple</td>
        <td>7</td>
    </tr>
    <tr>
        <td>Berries</td>
        <td>3</td>
    </tr>
</table>

We're using the border and cellpadding attributes inside the table tag just to make it pretty for now but this should be done 
a different way using CSS. By default a table won't have any borders around the cells. 

Without those attributes it looks like this:

<table>
    <tr>
        <td>Type of fruit</td>
        <td>Number of pieces</td>
    </tr>
    <tr>
        <td>Orange</td>
        <td>4</td>
    </tr>
    <tr>
        <td>Apple</td>
        <td>7</td>
    </tr>
    <tr>
        <td>Berries</td>
        <td>3</td>
    </tr>
</table>








