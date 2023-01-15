# Code 301 Reading Notes

[Class 1](https://mel-johnston.github.io/reading-notes/301/class1) -
[Class 2](https://mel-johnston.github.io/reading-notes/301/class2) -
[Class 3](https://mel-johnston.github.io/reading-notes/301/class3) -
[Class 4](https://mel-johnston.github.io/reading-notes/301/class4) -
[Class 5](https://mel-johnston.github.io/reading-notes/301/class5) -
[Class 6](https://mel-johnston.github.io/reading-notes/301/class6) -
[Class 7](https://mel-johnston.github.io/reading-notes/301/class7) -
[Class 8](https://mel-johnston.github.io/reading-notes/301/class8) -
[Class 9](https://mel-johnston.github.io/reading-notes/301/class9) -
[Class 10](https://mel-johnston.github.io/reading-notes/301/class10) -
[Class 11](https://mel-johnston.github.io/reading-notes/301/class11) -
[Class 12](https://mel-johnston.github.io/reading-notes/301/class12) -
[Class 13](https://mel-johnston.github.io/reading-notes/301/class13) -
[Class 14](https://mel-johnston.github.io/reading-notes/301/class14) -
[Class 15](https://mel-johnston.github.io/reading-notes/301/class15)

---

## Class 10 Notes - Persistence

### [Understand the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

1. What is a ‘call’?
    - A call is a function invocation (call) expression.
2. How many ‘calls’ can happen at once?
    - One call can happen at a time.
3. What does LIFO mean?
    - LIFO means Last In, First Out
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
          
        function firstFunction(){
          throw new Error('Stack Trace Error');
        }

        function secondFunction(){
          firstFunction();
        }

        function thirdFunction(){
          secondFunction();
        }

        thirdFunction();

5. What causes a Stack Overflow?
    - A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

### [JavaScript Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

1. What is a ‘reference error’?
    - A reference error is when you try to use a variable that is not yet declared.
2. What is a ‘syntax error’?
    - A syntax error is when you have something that cannot be parsed in terms of syntax.
3. What is a ‘range error’?
    - A range error is when you try to manipulate an object with some kind of length and give it an invalid length.
4. What is a ‘type error’?
    - A type error is when the types (number, string, etc.) you are trying to use or access are incompatible.
5. What is a breakpoint?
    - A breakpoint is a point in your code where you can pause execution and inspect the values that are stored in your variables.
6. What does the word ‘debugger’ do in your code?
    - The debugger keyword stops the execution of your code, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger.

### Bookmark and Review

- [JavaScript erroes reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)