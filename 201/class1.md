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

## Class 1 Notes -

### Getting Started

Read the following sections of JavaScript Basics: Start at “What is JavaScript?”, read through “Comments” section.

- Compose a short poem describing how HTTP sends data between computers.

  HTTP spider goes up the browser's web

  Down comes request and sends the spider back 

  Out comes the info and sends it to the site

  HTTP spider goes up and does it again

- Describe how HTML, CSS, and JS files are “parsed” in the browser. The browser parses the HTML file first, and that leads to the browser recognizing any `link`-element references to external CSS stylesheets and any `script`-element references to scripts. As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `link` elements, and any JavaScript files it has found from `script` elements, and from those, then parses the CSS and JavaScript.

- How can you find images to add to a Website? The easiest way to find images is through Google images, but you need to be sure use the license filter tool and select #Creative Commons licenses#

- How do you create a String vs a Number in JavaScript? A string is a sequence of text that is signified by being inside single quotes: 'this is a string'. A number is differentiated from a string by simply being...a number: 20193.

- What is a Variable and why are they important in JavaScript? Variables are containers that store values. Variables are necessary to do anyting interesing in JavaScript. 

---

### Intro to HTML

- What is an HTML attribute? Attributes contain extra information about the element that won't appear in the content.
  An attribute should have:
    - A space between it and the element name. 
    - The attribute name, followed by an equal sign.
    - An attribute value, wrapped with opening and closing quote marks.

- What is the Difference between `article` and `section` element tags? An `article` encloses a block of related content that makes sense on its own without the rest of the page. A `section` is similar to `article`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality or a theme. 

- What Elements does a “typical” website include? A typical website will probably inclue these elements:

         <!DOCTYPE html>
        <html lang="en-US">
         <head>
           <meta charset="utf-8" />
           <title>My test page</title>
         </head>
          <body>
           <p>This is my page</p>
        </body>
        </html>


- How does metadata influence Search Engine Optimization?

  Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines.

- How is the `meta` HTML tag used when specifying metadata?

  Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the `meta` element. 

### Misc

- What is the first step to designing a Website?
  The first step is to figure out what you want your website to do. From there you can make a plan of how to make your website.

- What is the most important question to answer when designing a Website?
  What exactly do I want to accomplish?

- Why should you use an `h1` element over a `span` element to display a top level heading?
  Semantics refers to the meaning of a piece of code. Most browsers have a default stylesheet and therefore knows how to style `h1` appropiately. 

- What are the benefits of using semantic tags in our HTML?
  Using semantic tags saves you time from having to style every single element on your page. It helps keep things organized and consistent. 

- Describe 2 things that require JavaScript in the Browser?
  Storing data as a variable and manipulating that data as a calculation
  
- How can you add JavaScript to an HTML document?
  JavaScript is applied to your HTML page in a similar manner to CSS. Whereas CSS uses `link` elements to apply external stylesheets and `style` elements to apply internal stylesheets to HTML, JavaScript only needs one friend in the world of HTML — the `script` element.
