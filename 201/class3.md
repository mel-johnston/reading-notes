# Code 201 Reading Notes

[Class 1](https://mel-johnston.github.io/reading-notes/201/class1) -
[Class 2](https://mel-johnston.github.io/reading-notes/201/class2) -
[Class 3](https://mel-johnston.github.io/reading-notes/201/class3) -
[Class 4](https://mel-johnston.github.io/reading-notes/201/class4) -
[Class 5](https://mel-johnston.github.io/reading-notes/201/class5) -
[Class 6](https://mel-johnston.github.io/reading-notes/201/class6) -
[Class 7](https://mel-johnston.github.io/reading-notes/201/class7) -
[Class 8](https://mel-johnston.github.io/reading-notes/201/class8) -
[Class 9](https://mel-johnston.github.io/reading-notes/201/class9) -
[Class 10](https://mel-johnston.github.io/reading-notes/201/class10) -
[Class 11](https://mel-johnston.github.io/reading-notes/201/class11) -
[Class 12](https://mel-johnston.github.io/reading-notes/201/class12) -
[Class 13](https://mel-johnston.github.io/reading-notes/201/class13) -
[Class 14](https://mel-johnston.github.io/reading-notes/201/class14) -
[Class 15](https://mel-johnston.github.io/reading-notes/201/class15)


---

## Class 3 Notes - 

### HTML - OL and UL

Unordered lists are used with items that don't have numerical ordering. They are usually displayed with a bullet. 
You can change the bullet style of `ul` by using the CSS property `list-style-type`. There are a few set options, or you can even add your own image. 
Ordered lists are best to use when you want your items to be numbered. Unordered lists simply have bullets (or your chosen icon/image). You can also nest one inside the other.
For ordered lists, you can change the `type` to numbers, letters, and Roman numerals.

### CSS - The Box Model

Imagine it's Christmas morning and you are opening a present. First you have to unwrap the gift wrapping on the outside - this is the `margin`. Once you take off the gift wrapping, there is the cardboard box. This is the `border`. Once you open the box there is bubblewrap protecting your present. The bubblewrap represents the `padding`. You remove the bubblewrap and finally you've gotten to your present - this is the content!

### JS - Arrays, Operators & Expressions, Conditionals, Loops

Arrays can store various data types — strings, numbers, objects, and even other arrays.

This is an array inside an array, which is called a multidimensional array. You can access an item inside an array that is itself inside another array by chaining two sets of square brackets together.

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 

In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings. The shorthand assignment operator += can also be used to concatenate strings.

`&&` - AND; allows to you chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true. `||` — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.

A relational operator compares its operands and returns a Boolean value based on whether the comparison is true. The `in` operator returns true if the specified property is in the specified object.

The comma operator (,) evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a `for` loop, to allow multiple variables to be updated each time through the loop. It is regarded bad style to use it elsewhere, when it is not necessary.

let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b; = 10dog

 When numbers and string are added today, wince they are different items, they are simply smushed together. 

Code needs to make decisions and carry out actiosn according to different inputs. This is where conditionals come in. In a weather app, if it is being looked at in the morning, show a sunrise graphic; show stars and a moon if it is nighttime. 

Most of the time when you use a loop, you will have a collection of items and want to do something with every item.

#### Things I want to know more about

Real world uses of arrays