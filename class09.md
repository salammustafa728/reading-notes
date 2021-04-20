# Readings : Forms and JS Events

# Forms

**Types of Forms** 
- ADDING TEXT: Text input: used for single line of text like email address
- Ma king Choices: It have 3 types:
    - Radio Button.
    - CheckBox.
    - Drop-down Box
- Submitting Forms: It have 2 types: 
   - Submit Button
   - Image Button.
- Uploading Files: It like file upload.

![forms](https://mobile.htmlgoodies.com/imagesvr_ce/1902/HTML%20Form.PNG)

It used when we take information from the user and the user press enter to confirm. Like login.

**Form Structure** 
`<form>` tag to This element should always carry the action attribute and will usually have a method and id attribute too. It have 2 attributes:
- action
- method

**Text Input**
`<input>` use to to create several different form
controls.
- type="text": When the type attribute has a value of text, it creates a singleline text input. and it have several types you can used like(datememail,password).
- name: When users enter information into a form, the server needs to know which form control each piece of data was entered into.
- maxlength: You can use the maxlength attribute to limit the number of characters a user may enter into the text field.

Text Area: `<textarea>`: is used to create a mutli-line
text input.

**Button & hidden Controls**
`<button>`was introduced to allow users more control over how their buttons appear. type="hidden":These form
controls are not shown on the page.


`<label>`it have the indicating purpose of each text input. 

> Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
`<form>` element.
>Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.

You can make style for the text input using css and changing the (font,color,background-color,border,..).

![styleForms](https://uicookies.com/wp-content/uploads/2018/03/contact-form-4-free-html-contact-forms.jpg)

List-style: We have a lot of property to style the listes. like (list-style-position,list-style-image,list-style-type) to make it more attractive.

Tables property: We have a lot of property to control or styling the tables like(width,padding,text-transform,letter-spacing, font-size) 


#  JS Events

![](https://www.edureka.co/blog/wp-content/uploads/2019/09/Events-in-JavaScript.jpg)


It happen when you make thing in the browser, so its the way the broser tell you you had done something.

Event Type: 
* UI Events:
   - load: web page has finish loading.
   - unload Web page is unloading.
   - error Browser encounters a JavaScript error or an asset doesn't exist.
   - resize Browser window has been resized.
   - scroll User has scrolled up or down the page.
* KEYBOARD EVENTS:
   - keydown User first presses a key.
   - keyup User releases a key
   - keypress Character is being inserted
* MOUSE EVENTS:
   - click User presses and releases a button over the same element
   - dbl click User presses and releases a button twice over the same element
   - moused own User presses a mouse button while over an element
   - mouseup User releases a mouse button while over an element
   - mousemove User moves the mouse (not on a touchscreen)
   - mouseover User moves the mouse over an element (not on a touchscreen)
   - mouseout User moves the mouse off an element

![Events](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

Using Parameters With Event Handelers & Listners:
you can passing the arguments that is requires a workaround.

![events](https://itzone.com.vn/wp-content/uploads/2019/06/Event-in-Javascript-1.png)

The Event Object: it tells you information about the event, and the element it happened upon.

Changing Default Behavior: It has methods that change:
the default behavior of an element.

Mutation events & observers: It happen Whenever elements are added to or removed from the DOM.

[Home](README.md)