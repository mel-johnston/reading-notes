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

## Class 10 Notes - What Went Wrong?

### Troubleshooting

Name some key differences between a Syntax Error and a Logic Error.

- These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. 
- These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. 

List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

- I've gotten many "undefined" errors because I didn't make the text inside an array a string.
- Also, many "x is not a function" because I forgot to add () when creating the function
- Since my code has been short so far, I just go line by line to figure out what typo/syntax error I've made
- Knowing how to troubleshoot will only become more important as we progress through the course and into the workforce. You won't just be troubleshooting your own code or projects you're familiar with, but also working on teams and partner programming that requires you to be meticulous.

### JavaScript Debugger

The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

A breakpoint is something you set to cause execution. It allows you to troubleshoot and find which part of your code isn't working properly. 

The Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.

The final section, Scopes, shows what values are visible from various points within your code.

#### Things I want to know more about

More easy shortcuts and tips for being able to troubleshoot better