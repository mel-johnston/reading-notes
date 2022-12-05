# Code 201 Reading Notes

[Class 1](https://melanie-johnston.github.io/reading-notes/201/class1) -
[Class 2](https://melanie-johnston.github.io/reading-notes/201/class2) -
[Class 3](https://melanie-johnston.github.io/reading-notes/201/class3) -
[Class 4](https://melanie-johnston.github.io/reading-notes/201/class4) -
[Class 5](https://melanie-johnston.github.io/reading-notes/201/class5) -
[Class 6](https://melanie-johnston.github.io/reading-notes/201/class6) -
[Class 7](https://melanie-johnston.github.io/reading-notes/201/class7) -
[Class 8](https://melanie-johnston.github.io/reading-notes/201/class8) -
[Class 9](https://melanie-johnston.github.io/reading-notes/201/class9) -
[Class 10](https://melanie-johnston.github.io/reading-notes/201/class10) -
[Class 11](https://melanie-johnston.github.io/reading-notes/201/class11) -
[Class 12](https://melanie-johnston.github.io/reading-notes/201/class12) -
[Class 13](https://melanie-johnston.github.io/reading-notes/201/class13) -
[Class 14](https://melanie-johnston.github.io/reading-notes/201/class14) -
[Class 15](https://melanie-johnston.github.io/reading-notes/201/class15)


---

## Class 6 Notes - Problem Domain, Objects, and the DOM

### JavaScript Object Basics

- An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).
- It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.
- Objects can contain arrays, and other data, in a more organized way.
- Dot notation and bracket notation are basically the same thing. Dot notation is preferred because it is shorter and easier to read. However, if the object property name is in a variable, then you can't use dot notation.
- `this` is a keyword and it refers to the current object the code is being written inside. So for the example, `this` refers to the variable `dog`. This is useful when you have multiple object literals and want to repeat a code without manually changing each `this`. 


### Intro to DOM

- DOM
 - The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.
 - It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
 - The DOM is built using multiple APIs that work together. 

- JavaScript & DOM
 - Code is written in JavaScript, but uses the DOM to access the document and its elements.
 - The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. 
 - DOM can be used with other coding languages, such as Python. 


 #### Things I want to know more about

 - Hands on use of DOM 