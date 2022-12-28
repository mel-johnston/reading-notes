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

## Class 7 Notes - Object-Oriented Programming, HTML Tables

### Domain Modeling

Domain modeling is used because it creates a defined layout that can be applied. Much like a function that is created and re-used in code, domain modeling creates a model that allows us to plug in certain data without having to re-create a whole framework of code each time. 

### HTML Table Basics

Why should tables not be used for page layouts?

- They should not be used as a layout tool
- They reduce accessibility for screen readers (if used as layout instead of data)
- They're not responsive

List and describe 3 different semantic HTML elements used in an HTML `table`.

- You have to start your table with `table`.
- To begin a new row, use `tr`
- Under `tr`, each `td` is an individual cell. 


      <table>
        <tr>  
          <td>I am the first cell of a table</td>
          <td>I am the second cell of a table</td>
          <td>I am the third cell of a table</td>
        </tr>
      </table>

### Intro to Constructors

What is a constructor and what are some advantages to using it?

- A constructor is a framework for an object. It allows us make one set of code that can be used with as many objects as we want, without having to rewrite an object literal each time.
- It reduces the amount of code written, which saves time, and provides clarity when viewing the code.

How does the term `this` differ when used in an object literal versus when used in a constructor?

- When used in the constructor and the constructor is called, it will bind `this` to the new object

Things to note: constructors should start with a capital letter.

### Object Prototypes Using A Constructor

I'll update this later when I have a more thorough understanding of constructors and inheritance. 

#### Things I want to know more about:

Arrow functions