# Readings : HTML Lists, Control Flow with JS, and the CSS Box Model

**HTML provise three type of lists**

* `<ol>` Ordered lists: each item in this list numbered. And each item in the list is placed
between an opening `<li>` tag and a closing `</li>` tag.


* `<ul>` are lists that begin with a bullet point.
The unordered list is created with the `<ul>` element. And each item in the list is placed
between an opening `<li>` tag and a closing `</li>` tag.

![ul/ol](https://wpastra.com/wp-content/uploads/2017/11/bullet-lists-code.png)

* Definition Lists: are made up of a set of terms along with the definitions for each of those terms.
`<dl>` is consists of a series of terms and their definitions. Inside the `<dl>` element you will
usually see pairs of `<dt>` (the definition term).and`<dd>` (This is used to contain the definition)elements.

![dl](https://www.w3resource.com/w3r_images/html-definition-list.png)



**Nested Lists: ** You can put a second list inside an `<li> `element to create a sublist
or nested list.

![Nested Lists](https://i.stack.imgur.com/bjuI6.png)


>Ordered lists use numbers.

>Unordered lists use bullets.

>Definition lists are used to define terminology.


**CSS Box Model**


**Boxes** the box is sized big enough to hold its contents. To set the box dimensions you can use the height and width properties.
* There is a max-width property indicates the maximum width. and min-width property to make sure that they do not appear too narrow.

* Overflow it tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
    * hidden: it hides any extra content that does not fit in the box.
    * scroll: it adds a scrollbar to the box so that users can scroll to see the missing content. 

    ![overflow](https://codebridgeplus.com/wp-content/uploads/Csslist2_overflow.png) 

    **Every boxes has three available properties:**

     * Border: The border separates the edge of   one box from another.
     * Margin: Margins sit outside the edge of the border.
     * Padding: is the space between the border of a box and any content contained within it.

     The Border have very properties like:
     The border-width: it has 3 values: thin,medium,thick.

     You can control the individual size of borders using four separate properties:
     border-top-width
     border-right-width
     border-bottom-width
     border-left-width

`border-style`: it control the style of a border using the border-style property.And it has a lot of properties.

`border-color` You can specify the color of a
border using either RGB values, hex codes or CSS color names.
   * border-top-color
   * border-right-color
   * border-bottom-color
   * border-left-color

**display** allows you to turn an inline element
into a block-level element or vice versa, and can also be used to hide an element from the page.
it have a prperities like inline,block,inline-block,none.

**visibility** The visibility property allows
you to hide boxes from usersbut It leaves a space where the element would have been. It take a properites like hidden,visible,

**border-image** The border-image property
applies an image to the border of any box. It takes a background image and slices it into nine
pieces.

**box-shadow** allows you to add a drop shadow
around a box.it has a lot of properites Horizontal offset,Vertical offset,Blur distance,Spread of shadow.

**border-radius** the ability to create rounded corners on any box.
You can specify individual values
for each corner of a box using:
border-top-right-radius,
border-bottom-right-radius,
border-bottom-left-radius,
border-top-left-radius.

>You can also control the borders, margin and padding for each box with CSS.

***JavaScript*** 

**USING QUOTES INSIDE A STRING** You can use single or double qoutes but the standred is single qoutes.and also you can use escaping by
using a backwards slash.before any type of
quote mark that appears within a string.

**USING A VARIABLE TO STORE A BOOLEAN**A Boolean variable can only have a value of true or fa1se,and tou can store it in a varaible.

**Declaring A Varaibles** There is a three way to declare a varaibles:
* Declare Variables and assigned a values into it.
* More than one variable are declared on the same line, then values assigned to each.
* Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line.

![varaibles](https://www.wikihow.com/images/5/57/Declare-a-Variable-in-Javascript-Step-24.jpg)


![varaibles](https://tutorial.techaltum.com/images/js-variables.jpg)

You can change the value that you assign to the variables later in the same script if you want.

**COMPARING TWO EXPRESSIONS**

You can compare two expressions in several ways,

* First way: var comparison= (score!+ score2) > (highScorel + highScore2);
* second the logical operator allow you to comparethe results of more than one comparison operator.

![comparing_expression](https://image.slidesharecdn.com/javascriptcomparisonandlogicaloperators-130122010359-phpapp01/95/javascript-comparison-and-logical-operators-7-638.jpg?cb=1358816684)

**Logical Operator**

![logical_operator](https://media.geeksforgeeks.org/wp-content/uploads/Operators.png)


**If-Statement** provide two set of code:
      * if the condition is true. 
      * if the condition is false.


![ifstatement](https://miro.medium.com/max/348/1*eChmTRd_YHgw-BE7qnUktA.png)

![ifelsestatement](https://miro.medium.com/max/1968/1*uENzVnU4d_rXpuoe9q1jsw.png)

**Switch-Statement** begin with a variable called switch value and each case have a possible value for this variable. The code run if the variable matches the value.
 
 ![switch](https://i.ytimg.com/vi/a9Q765OAKT4/maxresdefault.jpg)


Type coercion, every value in JavaScript
can be treated as if it were true or false; and
this has some interesting side effects.
Falsy values are treated as if they
are fa1se.
Truthy values are treated as if
they are true.

**Loops**

It used to repeatedly run a block of code until a certain condition is met.

* **For** loop:  repeats until a specified condition evaluates to false

![forloop](https://www.homeandlearn.co.uk/javascript/images/chapter_3/for_loops.gif)


[Home](README.md)



