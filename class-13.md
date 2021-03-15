# **[ Local Storage ]**


![multimedia](https://blog.teamtreehouse.com/wp-content/uploads/2013/01/localstorage-feature.png)

(The past, present & future of local storage for web applications)
<hr>

## **Intro**

Today, we're talking HTML5.. Let's go!

What do we really want when it's related to storage?

* A lot of storage space
* On the client
* That persists beyond a page refresh
* Isn’t transmitted to the server

Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

## **#1 [ A brief history of local storage hacks before HTML5 ]**

In the beginning, there was only Internet Explorer. Microsoft invented a great many things and included them in their browser, Internet Explorer. One of these things was called **DHTML Behaviors**, and one of these behaviors was called **userData**.

* **userData** allows web pages to store up to 64 KB of data per domain

* In 2002, **Adobe** introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as **Local Shared Objects**.

* By 2006, with the advent of ExternalInterface in Flash 8. Flash gives each domain 100 KB of storage “for free.”

* In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.

* By 2009, **dojox.storage** could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

<hr>

## **#2 [ Introducing HTML5 storage ]**

HTML5 Storage is a specification named Web Storage. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”

**So, what exactly is it?** Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site. But unlike cookies, this data is never transmitted to the remote web server.

<hr>

## **#3 [ Using HTML5 storage ]**

HTML5 Storage is based on named key/value pairs. You _**store**_ data based on a named key, then you can retrieve that data with the same key.

There are also methods for _**removing**_ the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

Finally, there is a property to _**get the total number**_ of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).

Also, you can track those changes in storage programmatically.

* The storage event is not cancelable; It’s a way for the browser to tell you, _“hey, this just happened. There’s nothing you can do about it now; I just wanted to let you know.”_

<hr>

## **#4 [ Beyond named key-value pairs: competing visions ]**

While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices.

<br>

![browsers](https://www.lambdatest.com/blog/wp-content/uploads/2018/03/534-x-300.gif)

### **What do different browsers have to say about IndexedDB?**

At time of writing, IndexedDB has only been implemented in a beta version of Firefox 4.

(By contrast, **Mozilla** has stated that they will never implement Web SQL Database.) **Google** has stated that they are considering IndexedDB support for Chromium and Google Chrome. And even **Microsoft** has said that IndexedDB “is a great solution for the web.”

* So what can you, as a web developer, do with IndexedDB? <br>At the moment, virtually nothing beyond some technology demos. A year from now? Maybe something. Who knows..

<br>

**_NOTE_: If you find yourself interested in seeing HTML5 storage in action, don't hesitate to check out the source bellow. Which is also rich with other sources.**

<hr>

Source:
* [The past, present & future of local storage for web applications](http://diveinto.html5doctor.com/storage.html)
