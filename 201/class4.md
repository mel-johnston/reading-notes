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

## Class 4 Notes - 

Notes go here

### HTML

A link is created by wrapping the text insde an `<a>` element and using the `href` attribute (Hypertext Reference), that contains the web address. To make links accessible (like to those with screen readers), be descriptive in where the link is directing and what it is (a download and what size).

### CSS

Normal flow is the way that webage elements lay themselves out if you haven't changed their layout. 

By default, a `block level` element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content.

The size of `inline` elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements — except for images. Unlike other inline elements, images can be resized without changing their display property. If you want to control the size of an inline element in this manner, you need to set it to behave like a block level element (e.g., with display: block; or display: inline-block;, which mixes characteristics from both).

Static positioning is the default for every html element. 

Advantages to using absolute positioning on an element:

 - You can create isolated UI features that don't interfere with the layout of other elements on the page.
 - For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.

Key difference between fixed positioning and absolute positioning:

- They work exactly the same except key difference: whereas absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport. 


### JavaScript

Invoking a function is done by including the name of the function in the code somewhere, followed by (). This is also known as function declaration. 

What is the difference between a parameter and an argument?

- Parameters are sometimes required with functions. These values need to be included inside the funtion's (). 

- There is no difference - parameters are sometimes called arguements, properties, or even attributes.  

### Misc

Pair programming is very common and benefical to coding. The main benefit is the efficiency. With two (or more) people working on the same project, there's the ability to help each other and work through problems as they come up, instead of one person struggling for a long time. Secondly, there is the accountability to keep each other on track and focused on the main goal, especially when there are time constraints. 

#### Things I want to know more about

More parameters and examples