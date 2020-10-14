# Code Fellows Day 13 Reading

## Local Storage

### History

- web applications were at a disadvantage vs native applications when storage was considered.
- Cookies were invented early and were used for local storage but had downsides: slowing down the application, sending unecypted data out into the internet, and limited storage.
-  Internet Explorere had `userData` but there wasn't a way to increase storage and storage was small
- Adobe created flash 6  but had limits due to design quirks 
- Gears open source plugin from google which stores data in SQL database tables after getting permissions from the user once

- ***all theses solutions were specific to a single browser or relaint on 3rd party plugin -- not ideal***

- HTML5 is trying to solve this issue

- HTML5 Storage is a way for web pages to store named key/value pairs locally within the client web browser. 
- data is stored after the site is closed, but never passed to the internet unless the user sends it manually  
- it can be used wih most browsers
- you can access it with the `localStorage` object on the global window object.
- good idea to detect if the browser supports it before using it.
- data is only stored as a string so you will need to convert to boolean or use `parseInt` to change to a number
- to see if something changed you need to trap the storage event only tell you is something changes but it will not change if you set an item to its existing value.
- only 5 megabytes of storage and you can not ask for more

***Other Ways of Storage***

SQL
- no standard for the code so this is a difficult solution until standarization exists.


[<-- Back](README.md)