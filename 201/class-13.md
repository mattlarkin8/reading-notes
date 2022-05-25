# **Local Storage**

## **The Before Times**

Before HTML5, there was not much at all in the way of persistent local storage for web browsers. Cookies were one of the earliest forms of storage, but they didn't really provide that much storage and had some drawbacks. There were some different attempts to build local storage systems for browsers, but none of them ever really achieved the desired result. They were all either browser specific or plugin reliant, none of which created anything close to a global solution. Even though `dojox.storage` was able to auto-detect different browsers and plugins, it was still only able to present a unified interface **on top** of those many underlying factors. Nothing had yet managed to create the real solution: an API that could be used natively across all browsers without third-party plugins.

## **HTML5 Storage**

Web Storage, also called Local Storage or DOM Storage, is the storage solution put forth by HTML5. It allows web pages to store key/value pairs locally within the browser. This data persists whether you leave page, close the browser, or restart your computer. It is implemented natively across all modern web browsers and doesn't require any for plugins.

This storage method is based on key/value pairs where the key for that data is stored as a string. The data is also stored as a string, so keep that in mind for the storage of other data types. You can use the `storage` event to keep track of when changes are made and/or create some other event handler that triggers upon storage event.

## **Things I want to know more about**

I think I understand the basic concepts pretty well, but I don't know too much about really using any commands for the storage or even how to really use the storage itself. I a looking forward to going over it more in class and getting some concrete examples. Once I have gotten some experience with this storage method, I'm sure it will become an important piece of my future programs.
