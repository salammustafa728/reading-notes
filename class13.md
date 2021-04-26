# Read: 13 - Local Storage

Local Storage is one of the advantages of web applications, and operating system a layer for for storing and retrieving data from application like preferences or runtime state. That files  stored in the registry, INI files, XML files, or some other place according to platform convention. New storage for web application is Cookies it can be used as local storage of small amount of data.

Cookies have have three potentially dealbreaking downsides:
- Its include with every HTTP request, and it slowing down your web application because it transmitting the same data over and over.
- Its include with every HTTP request so it sending data unencrypted over the internet.
- Its limited data 4 KB of data.

Breif Hestory about local storage. There was a browser-wars, and Microsoft invented a great many thing one of them is are DHTML behaviour one of this is **userData**.

**userData** it allow the web page to store up 64 KB of data per domain.

In 2002 Adobe invent flash cookie known as Local Shared Objects allow flash objects to store up to 100 KB of data. Then brad Neubrg develop Flash To JavaScript called(AJAX). Then By 2006 ExternalInterface
then AMAAS integrated it into Dojo Toolkit its Flash gives each domain 100 KB of storage for free. In 2007 Gears provides an API to an embedded SQL database based on SQLite. Then come the a third-party plugin. after that  HTML5  comes to solve all the problem in the previous versions and API'S .

**INTRODUCING HTML5 STORAGE** 
HTML5 Storage its web page to store key /value pairs locally within the client web browser. its like cookies these data persists even after you navigate away from the web site. And every browser supports HTML5 Storage. To use HTML5 storage based on named key/value pairs, you can store data in key and you can retrive data with the same key, the key is string but the value can be any type of values supported by JavaScript and  If you are storing and retrieving anything other than strings, you should use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
And you can use setItem() and getItem() also you have  clear() method and removeItem() and key() to get the total value in storage.

To keep track programmatically of when the storage area changes you can trap the storage event, and its fired on the window object whenever setItem(), removeItem(), or clear() is called. and its supported everywhere .

We have storage objects like key,oldvalue,newvalue and url*. 
And of HTML5 Storage API has been standardized and implemented.
And you have SQL statement like  SELECT, UPDATE, INSERT, and DELETE its backend programming. in HTML5 you have IndexedDB is a great solution for the web.


[Home](README.md)



