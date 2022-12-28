## Code 102 Reading Notes

[Class 1](https://mel-johnston.github.io/reading-notes/102/class1) -
[Class 2](https://mel-johnston.github.io/reading-notes/102/class2) -
[Class 3](https://mel-johnston.github.io/reading-notes/102/class3) -
[Class 4](https://mel-johnston.github.io/reading-notes/102/class4) -
[Class 5](https://mel-johnston.github.io/reading-notes/102/class5) -
[Class 6](https://mel-johnston.github.io/reading-notes/102/class6) -
[Class 7](https://mel-johnston.github.io/reading-notes/102/class7) -
[Class 8](https://mel-johnston.github.io/reading-notes/102/class8)

---

### Class 5 Notes - Design Web Pages with CSS

Cascading Style Sheets (CSS) allows you to bring your website to life with color, design, and organization. 

Most common, and best practice, is to link an external CSS file to your HTML. This will go in the `<head>` as shown below:

        <!DOCTYPE html>
        <html>
        <head>
        <link rel="stylesheet" href="stylesheet.css">
        </head>
        <body>

Styling with CSS in the HTML document is possible, but generally not recommended. 

Here is how CSS should look:

        selector {
            property: property value;
        }

Using this format, let's change the `color` and `size` of fonts:

        h1 {
            color: green;
            font-size: 5px;
        }

There are some basic CSS properties that are easy to remember, however using a resource like [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS) will help you discover all the possibilities.


Finally, every web browser comes with preset CSS, like when you use `h1` and it shows a (mostly) standard Header 1 on the page. If you want to start from scratch, there is a tool call [Reset CSS](https://meyerweb.com/eric/tools/css/reset/). This is cancel out everything. You can copy this to the top of your own CSS page, then continue with your own CSS to make your page look exactly how you want. 


#### Things I want to know more about: 
- Flexbox