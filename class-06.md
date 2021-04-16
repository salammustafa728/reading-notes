# Read: 06 - JS Object Literals; The DOM

# Objects

Object Methods:Methods are stored in properties as function definitions. A method is a function stored as a property. and when you declare a function you can Calling function that need information: when you call a function you spicify a parameter that should be inside parentheses that follow its name.



The parameter is the values inside the function parentheses when we declared it for the first time.
The argument is the values that we assign it to the function when we invoked it.
And some function return information to the code.



![obj](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3OWcPQx-UoduUaftLIT4jxTmbuls5sMmP1N1ZAiediw27--DvAw15u8_obgSl38YnsOk&usqp=CAU)

![objprop](https://dmitripavlutin.com/static/50a87420915de18f26da616865fe9825/05127/access-object-properties-2.png)

Variable Scope
![variableScop](https://ringojs.org/documentation/images/scriptscope.png)

The variable have two type, 
* Local variable that declare in a scop of code block and we can't access it from outside the block.
* Global variable that in declared outside any block un the code so we can access it from any where in the code.

![var_scop](https://miro.medium.com/max/921/1*RKHHl0sjhqob-IE4RKrgqQ.png)

# The Document Object Model (DOM) 

Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

![dom](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)


![js_DOM](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Attribute-Nodes-in-JavaScript-DOM.jpg)

Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes.

![DOM](https://slideplayer.com/9755571/31/images/slide_1.jpg)

Method that select individual element :
getElementById() and queryselector(), both use a similar selector and search an entire document and return individual element.

![](https://slidetodoc.com/presentation_image_h/ffddfa9403a2a291f1b3ddd36a481c71/image-16.jpg)

![queryselector](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQTKkzzz8l1rgDn-K4QL1mIzzLXx7d-8bpzLg&usqp=CAU)

![pro_dom](https://image.slidesharecdn.com/understandingxmldom-120525121552-phpapp02/95/understanding-xml-dom-11-728.jpg?cb=1337948557)



NODELISTS: It's a queries that return more than
one element.

- getElementsByTagName('hl ' ): Even though this query only returns one element. the method
still returns a Nodelist because of the potential for returning more than one element.

- getElementsByTagName('li '): This method returns four elements, one for each of the`<li>` elements on the page. They appear in the same order as they do in the HTML page.

- getElementsByClassName('hot'): This Nodelist contains only three of the `<li >`elements because we are searching for elements by the value of their
cl ass attribute, not tag name.

- querySe l ectorA 11 ( ' l i [id]'): This method returns four elements, one for each of the `<li>` elements on the page that have an id attribute.

![loopingSelector](https://miro.medium.com/max/2016/1*Nw4HKokkOWb-2quyyRzOfA.png)

Adding element to the DOM tree by using the createElement() method that create element that can be added to the DOM tree. And createTextNode() method allows you to create a new text node to attach to an element. And The text node is added to
the new element node using appendChild().

Removing element from the Dom tree by using the The removeChild() method it takes one parameter: the reference to the element that you no longer want.

![htmldisplay](https://image.slidesharecdn.com/javascript-151005210949-lva1-app6892/95/java-script-14-638.jpg?cb=1444079563)


**CREATING & REMOVING ATTRIBUTES**
By using The setAttribute() method method allows you to update the value of any attribute.
And you can remove any arrtibut by using get ElementByld() method is used to retrieve the first item from this list.




[Home](README.md) 