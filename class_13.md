# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

![LocalStorage](https://www.designveloper.com/wp-content/uploads/2020/09/How-Progressive-Web-Apps-Can-Benefit-Online-Stores_.jpg)

#### Local Storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

#### Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over .

- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL) .

- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful .

-----------------------

## USING HTML5 STORAGE

![HTML5 Storage](https://scriptverse.academy/img/tutorials/html5-localstorage.png)

#### HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

#### The data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

#### Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

#### Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets.

#### There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

-----------------------------------

## TRACKING CHANGES TO THE HTML5 STORAGE AREA

![HTML5 MCQ](https://www.onlineinterviewquestions.com/storage/categories/August2020/html5-mcq.jpg)

#### The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)

### STORAGEEVENT OBJECT

 PROPERTY | TYPE | DESCRIPTION 
------------ | ------ | -----------
key | string | the named key that was added, removed, or modified
oldValue | any | the previous value (now overwritten), or null if a new item was added
newValue | any | the new value, or null if an item was removed
url | string | the page which called a method that triggered this change

