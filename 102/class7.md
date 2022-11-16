## Code 102 Reading Notes

[Class 1](https://melanie-johnston.github.io/reading-notes/102/class1) -
[Class 2](https://melanie-johnston.github.io/reading-notes/102/class2) -
[Class 3](https://melanie-johnston.github.io/reading-notes/102/class3) -
[Class 4](https://melanie-johnston.github.io/reading-notes/102/class4) -
[Class 5](https://melanie-johnston.github.io/reading-notes/102/class5) -
[Class 6](https://melanie-johnston.github.io/reading-notes/102/class6) -
[Class 7](https://melanie-johnston.github.io/reading-notes/102/class7) -
[Class 8](https://melanie-johnston.github.io/reading-notes/102/class8)

---

### Class 7 Notes - Programming with JavaScript

Control flow is the order in which the computer executes statements in a script. Code runs from the first line to the last line in a file, unless there are conditionals and loops. 

An example of script that requires a user to type in something:

        if (isEmpty(field)) {
        promptUser();
        } else {
        submitForm();
        }

JavaScript Functions

A function is a block of code that will perform a specific task. A function is executed when "something" invokes it. 

Example:

        // Function to compute the product of p1 and p2
        function myFunction(p1, p2) {
        return p1 * p2;
        }

JavaScript Operators

The Assignment Operator (=) assigns a value to a variable. 
        let x = 10;

The Addition Operator (+) adds numbers:

        let x = 5;
        let y = 2;
        let z = x + y;

The same goes for multiplying (*), division, (/), and subtraction (-). 


However, the `+` operator can be used to add strings. 

        let text1 = "John";
        let text2 = "Doe";
        let text3 = text1 + " " + text2;
        The result of text3 will be:

        John Doe

There are many more operators. For more detailed examples: [Expressions & Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)


---

#### Things I want to know more about:

- making my websites do fun things