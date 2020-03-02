 # local storage

## What is the local storage in html5?
There are two types of web storage, which differ in scope and lifetime:(Session Storage and Local Storage).
- The local storage uses the localStorage object to store data for your entire website on a permanent basis. That means the stored local data will be available on the next day, the next week, or the next year unless you remove it.
## USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

    interface Storage {
    getter any getItem(in DOMString key);
    setter creator void setItem(in DOMString key, in any data);   
    }; 

