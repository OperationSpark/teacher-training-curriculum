{"filter":false,"title":"More-HTML.md","tooltip":"/javascript-wiki.wiki/More-HTML.md","undoManager":{"mark":8,"position":8,"stack":[[{"group":"doc","deltas":[{"start":{"row":0,"column":0},"end":{"row":194,"column":0},"action":"insert","lines":["HTML","=====","","## Links, images, lists, and tables","","We're going to learn some more HTML elements in the following lesson. There are [many HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)","out there but you'll mostly use just a portion of them. ","","### Links","A link, also known as a hyperlink, is text, an image, or other element that when clicked on brings a user to another page. That page can be within the same ","site or to another site. ","","Links consist of three main parts: ","","* the `<a>` element","* the href atrribute which holds the URL","* and the URL","","A URL, or uniform resource locator, is a web address. `http://www.google.com` is a URL. When you type a web address into the browser to visit a website you ","are typing a URL. URLs are defined with the href attribute which you can see in use below.","","In HTML:","","`<a href=\"http://www.google.com\">This is a link to Google</a>`","","Actual link:","","<a href=\"http://www.google.com\">This is a link to Google</a>","","#### Step 1","","Open Lesson3.html, create an HTML page, and create a text link to Facebook. Save the page and view your link.","","**Two types of URLs:**","","Absolute URLs use the full web address such as `http://www.example.com/path/to/file` and are used when linking to external websites.","","Relative URLs use just the path to a page or file and omit the first part such as `path/to/file`. Relative URLs are used to link to other pages","within your website. There is no need to include the full path to your website in a link that is to another part of your website because","you're already on it. ","","### Images","The image element in HTML is one of the few with no closing tag because there is nothing to wrap the tags around. ","","`<img src=\"http://i.imgur.com/58eyAmw.jpg\" alt=\"Llama photo\">`","","<img src=\"http://i.imgur.com/58eyAmw.jpg\" alt=\"Llama photo\">","","There are two attributes here: src and alt. The **src** attribute is the source, or the location, of the image which comes in the form of a URL. The **alt** attribute is what will be displayed if for some reason the ","image isn't available or someone is using a screen reader. ","","#### Step 2 ","Create an image with HTML","","* In Lesson3.html create an image with HTML. ","* Find an image you like on Wikipedia. ","* Right click on the image and click \"Copy Image URL\" to get the URL. ","* Save the file and view your image. ","","#### Step 3 ","Create an image **link** with HTML","","* Create a link like you did in Step 1","* Instead of putting text inside that link, insert an image like the one you made in Step 2","* Save the file and click on your image link!","","### Lists","HTML lists are found all over the web. There's one directly above in Step 3. There are two types of lists: **unordered** and **ordered**.","","Unordered simply means the list will use bullet points. Ordered means it will display numbers next to each item instead of bullets. Ordered lists use the `<ol>` element while ","unordered lists use the `<ul>` element. Unordered lists are used much more often. Both types of lists use the same element to define items which is a list","item or `<li>` element.","","Unordered list:","","```html","<ul>","    <li>Orange</li>","    <li>Apple</li>","    <li>Banana</li>","</ul>","```","","<ul>","    <li>Orange</li>","    <li>Apple</li>","    <li>Banana</li>","</ul>","","Ordered list:","","```html","<ol>","    <li>Orange</li>","    <li>Apple</li>","    <li>Banana</li>","</ol>","```","","<ol>","    <li>Orange</li>","    <li>Apple</li>","    <li>Banana</li>","</ol>","","#### Step 4","","* Choose some items that would normally go in a list together.","* Create two lists in Lesson3.html like the examples above. ","* Save your work and view the lists. Notice how the lists are indented. ","","","### Tables","Tables are as old as the web, and prior to the advancement of CSS, were used to handle a lot of formatting and alignment on websites. Today tables","are mostly used to display what they should be...tabular data. ","","Tables have three main elements:","","* `<table>` defines the table itself","* `<tr>` defines a row (remember the r for table row)","* `<td>` defines a cell (td means tabular data)","","```html","<table border=\"1\" cellpadding=\"10\">","    <tr>","        <td>Type of fruit</td>","        <td>Number of pieces</td>","    </tr>","    <tr>","        <td>Orange</td>","        <td>4</td>","    </tr>","    <tr>","        <td>Apple</td>","        <td>7</td>","    </tr>","    <tr>","        <td>Berries</td>","        <td>3</td>","    </tr>","</table>","","```","","<table border=\"1\" cellpadding=\"10\">","    <tr>","        <td>Type of fruit</td>","        <td>Number of pieces</td>","    </tr>","    <tr>","        <td>Orange</td>","        <td>4</td>","    </tr>","    <tr>","        <td>Apple</td>","        <td>7</td>","    </tr>","    <tr>","        <td>Berries</td>","        <td>3</td>","    </tr>","</table>","","We're using the border and cellpadding attributes inside the table tag just to make it pretty for now but this should be done ","a different way using CSS. By default a table won't have any borders around the cells. ","","**Without those attributes it looks like this:**","","<table>","    <tr>","        <td>Type of fruit</td>","        <td>Number of pieces</td>","    </tr>","    <tr>","        <td>Orange</td>","        <td>4</td>","    </tr>","    <tr>","        <td>Apple</td>","        <td>7</td>","    </tr>","    <tr>","        <td>Berries</td>","        <td>3</td>","    </tr>","</table>","","","","","","","","",""]}]}],[{"group":"doc","deltas":[{"start":{"row":187,"column":0},"end":{"row":187,"column":99},"action":"insert","lines":["https://docs.google.com/forms/d/1w5_oDFD64REnUShfrmyoW8F466X-zPHIwwY6wQ3BM7o/viewform?usp=send_form"]}]}],[{"group":"doc","deltas":[{"start":{"row":186,"column":0},"end":{"row":187,"column":0},"action":"insert","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":187,"column":0},"end":{"row":188,"column":0},"action":"insert","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":187,"column":0},"end":{"row":188,"column":0},"action":"remove","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":187,"column":0},"end":{"row":188,"column":0},"action":"insert","lines":["",""]}]}],[{"group":"doc","deltas":[{"start":{"row":188,"column":0},"end":{"row":189,"column":0},"action":"insert","lines":["<a href=\"https://docs.google.com/forms/d/1XrMSTU5s7BAAWdwz5OY-Ec7POjGo4_W7sf7mMmfPa40/viewform?usp=send_form\" target=\"_blank\"><img src=\"https://raw.githubusercontent.com/OperationSpark/javascript-wiki/master/images/btn-quiz.png\" alt=\"Take the quiz\"></a>",""]}]}],[{"group":"doc","deltas":[{"start":{"row":190,"column":0},"end":{"row":190,"column":99},"action":"remove","lines":["https://docs.google.com/forms/d/1w5_oDFD64REnUShfrmyoW8F466X-zPHIwwY6wQ3BM7o/viewform?usp=send_form"]}]}],[{"group":"doc","deltas":[{"start":{"row":188,"column":9},"end":{"row":188,"column":108},"action":"remove","lines":["https://docs.google.com/forms/d/1XrMSTU5s7BAAWdwz5OY-Ec7POjGo4_W7sf7mMmfPa40/viewform?usp=send_form"]},{"start":{"row":188,"column":9},"end":{"row":188,"column":108},"action":"insert","lines":["https://docs.google.com/forms/d/1w5_oDFD64REnUShfrmyoW8F466X-zPHIwwY6wQ3BM7o/viewform?usp=send_form"]}]}]]},"ace":{"folds":[],"scrolltop":1987.5,"scrollleft":0,"selection":{"start":{"row":121,"column":0},"end":{"row":121,"column":0},"isBackwards":false},"options":{"guessTabSize":true,"useWrapMode":false,"wrapToView":true},"firstLineState":{"row":114,"state":"start","mode":"ace/mode/markdown"}},"timestamp":1418845618701,"hash":"05d5a967b3f5d028ec1b058a8d6639feef71abfe"}