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








