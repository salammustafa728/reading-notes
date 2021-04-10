# HTML, CSS and JavaScript

# HTML and CSS

![htmlandcss](https://www.edlibre.com/wp-content/uploads/apprendre-html-css-pour-les-nuls.jpg)

# HTML

**HTML** is the structure of the web pages you can add images,paragraph, forms, links, texts and tables.
![htmltags](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/HTML-Tags-df-1200x900.jpg)

![htmltags](https://rpf-futurelearn.s3-eu-west-1.amazonaws.com/Web+Dev/Illustrations/FL-WebDev-1.6-nested.png)

# CSS

**CSS** is the presentation of your work. The design to your web pages. It's control how to color texts, fonts and backgroung also how to control the position of the elements on the screen.

![css_ex](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

It's the main diffrent of *css* and *html* 

**How the web work** when you visit any website the hosting may be anywhere in the world, your browser will first connect to (DNS) Domain Name System. DNS tell youe browser how to find the website.
The steps of how the web work:
* you connect to the web by ISP (Internet Service Provider) by typing a web address or domain name into your browser.Example: google.com.
* Then your computer will connect to DNS this act like a phone books. It tell your computer the IP address which associated with the requested domain name. A IP address is a number up to 12 digits separated by periods / full stops. and every device has unique IP address.
* The uniqe number that the DNS return the your computer allows your browser to connect the web server that host the website you requested.
* The web server sends the page you requested back to your browser.

![webwork](https://media.geeksforgeeks.org/wp-content/uploads/20190927155217/webserver.png)

# Structure (HTML)
Structure are very important because it help the visitors of your website to know the message from your website that you want them to know.

you can display a text that you write it in a word document in the web page by using html tags 
The HTML made uo of characters that live inside angled brackets, called HTML elements. Elements made up of two tags:an opening tag and a closing tag. The closing tag has an extra forward slash in it. And each tells the browser something about the information that sits between its closing and opening tags.
![descriptionTags](https://image.slidesharecdn.com/htmltagsorderedbycategory-150314225950-conversion-gate01/95/html-tags-ordered-by-category-1-638.jpg?cb=1426374151)

![descriptionTags](https://lh3.googleusercontent.com/proxy/B_FAbAYt9vk2xJZxb5LbCdK5dGI4z8XMU_CZsoOAZ5hKhkFaC5Y6tUAOG53LbokXAmNhtovpnyVGQRaHHnL0cKXAoIaGK9LJ8GBwqPbPfGWomg) 
 
You can provide attributes to the element. The attributes provide additional information about the the content of the element. They appear in the opening tag and provide two parts: value and name.

![css_ex](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

**Create a web page on a PC**
* Open Notepad or install Notepad++ 
* Right HTML code start from <html> tag, don't forget to close it. 
* Then go to the file menu, choose save, save this file with extenion .html 
* Go to the file menu and select open, select the page and open it, it will open on the browser page.

**Comments** in HTML you can write a comment like this: <!-- -->  you can add your comment inside these characters. <!-- comment goes here -->
Comments make your code more professional.
And its not visible to the user.

**ID Attribute** every element in HTML carry an ID attribut, its used to identify that element from other elements. It's value must begin with a letter or underscore not a number or any other character. And It is important that no two
elements on the same page have the same value for their id attributes. Also is known as a global attribute because it can be used on any element.

**Class Attribute** Every HTML element can also carry a class attribute. you will want a way to identify several elements as being different from the other elements on the page.

**Bolck Element** the elements that always
appear to start on a new line in the browser window. Examples of block elements are
`<h1>`, `<p>`, `<ul>`, and `<li>`.

**Inline elements** Some of elements always
appear to continue on the same line as their neighbouring elements. Examples of inline elements are: 
`<a>`, `<b>`, `<em>`, and `<img>`.

![examples](https://www.differencebetween.com/wp-content/uploads/2018/02/Difference-Between-Block-and-Inline-Elements-fig-1.png)

* Some important tag in HTML to build the structure of the web page.

**Iframe** An iframe is like a little window that has been cut into your page. The main purpose of iframe is to display the google map into it.
It has alotof attribut need to specify: 
  * src: to put the URL of the page that you want to show in the frame
  * hieght: specifies the height in pixels.
  * width: specifies the width in pixels.
  * seamless: a new attribute called seamless can be applied to an iframe where scrollbars are not desired.

![iframe](https://i.stack.imgur.com/ZUi9z.gif)

**meta** It lives inside the <head> element and
contains information about that web page.
Some defined values for this attribute that are commonly used are:
  * description: This contains a description
     of the page.
  * keywords: This contains a list of             commaseparated words that a user might search on to find the page.   
  * robots: This indicates whether search
   engines should add this page to their search results or not.
  * author:This defines the author of the
     web page. 
  * pragma: This prevents the browser from
    caching the page.
  * expires: can be used to indicate when the page
    should expire.

 **Escap Character** are used to include special
characters in your pages.   

 ![escape_character](https://codebridgeplus.com/wp-content/uploads/html-entities.jpg) 

 **Navigation** nav:is used to contain the major navigational blocks on the site such as the primary site navigation.

 **Articles** acts as a container for any section of a page. 

 * The `<aside>` it may be in the article tag or outside, inside the article it should contain information about what is inside the artical, and when it's outside the article it acts as a container for content that is related to the entire page.
 
 * `The <section>` element it grouped the elements that is inside it.

 **Heading Groups** 
 * `<hgroup>` The purpose of the `<hgroup>` element is to group together a set of one or more` <h1>` through `<h6>` elements so that they are treated as one single heading.

* The `<figure> <figcaption>` , `<figure>` used to contain any content that is referenced from the main flow of an article (not just images) and it contain `<figcaption>` also.

* `The <div>` there is a new elemants that take it's place and it's grouped the elemant togther.

* The`<a>` to add a link to the website.

>HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.

**WireFrames** 
is a simple sketch of the key information that needs to go on each page of a site.

![wirframe](https://upload.wikimedia.org/wikipedia/commons/4/47/Profilewireframe.png)

Wireframes allow you to organize the information that will need to go on each page. 

You can use grouping and similarity to help simplify the information you present.

# JavaScript 
**JavaScript it makes the webpages interactive, interesting, and user-friendly.**

![Javascript](https://4.bp.blogspot.com/-PQHNOWFNS9o/XAkNsyPerCI/AAAAAAAALks/ONXxkKH3lRwskA3cfiqPa-cGKlt8u-l6wCLcBGAs/s1600/javascript.jpg)

A script is a series of instruction that you can followto achieve a goal. You can use the *javascript* to make your pages interactive by modifiying the content and markup used in the webpage while it is being viewed in the browser.

You can use JS to change the content of the *HTML* page while it's loaded in the browser
   * Access the content of the page.
   * Modifying the content.
   * Program the content.
   * React to events.
You can make a Slideshow or Forms 
**JavaScript Slidshow**
Slideshow display a number of different images within the same space in the page.They can play automatically as a sequence, or users can click through the slides
manually. 

**JavaScript Forms**
Validating forms it's important when the information supplied by users. *JavaScript* lets you to alert the user if thier is a mistake.

Defining a Goal & Designing the Script

This example calculates the cost of a name plaque.
Customers are charged by the letter.
  * The first thing you should do is detail your goals for the script.
  * Customers can have a name added to a plaque; each letter costs $5. When a user enters a name, show them how much it will cost.
  * Next, break it into a series of tasks that have to be performed in order to achieve the goals:
     * script is triggered when the button is clicked.
     * collect the name entered into the form field.
     * checks that the user has entered a value.
     * If the user has not entered anything, a message will appear telling them to enter a name. 
     * If a name has been entered, calculate the cost of the sign by multiplying the number of letters by the cost per letter.
     * Show how much the plaque costs.

    ![flowchart](https://www.yworks.com/assets/images/landing-pages/demo-flowchart-example.aaab9f9d.png)   

Sketching out the tasks in a flowchart
scripts will need to perform different tasks in different situations. You can use flowcharts to work out how the tasks fit together.

> flowcharts will help you understand how scripts work.

**OBJECTS** In computer programming, each physical thing in the world can be represented as an object. 

Each object can have its own:
* Properties
* Events
* Methods

**PROPERTIES** characteristics of an objects.
Each property has a name and a value.

**EVENT** code that run when an event occurs.

**Methods** represent things people need to do with objects. The code for a method can contain lots of
instructions that together represent one task.

>When you use JavaScript in the browser, The interpreter takes your
instructions and translates them into instructions the browser can use to achieve the tasks you want it to perform

>In an interpreted programming language, like JavaScript. each line of code is translated one-by-one as the script is run.

You can link the JS file with your HTML file by `<script>` tag, It has an attribute called src, whose value is the path to the script you created.

![script](https://i.ytimg.com/vi/dlfEPzjOl-4/maxresdefault.jpg)

HOW A BROWSER SEES A WEB PAGE: 
1. The browser recives HTML page.
2. It createsa model of the page stores it in memory.
3. It shows the page on screen using a rendering engine. 

[Home](README.md) 



