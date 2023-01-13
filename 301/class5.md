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

## Class 5 Notes - Conditional Rendering, Routing

### [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

- What is the single responsibility principle and how does it apply to components?
  - A component should ideally only do one thing
- What does it mean to build a ‘static’ version of your application?
  - Building out the UI with no interactivity
- Once you have a static application, what do you need to add?
  - To add interactivity, use state
- What are the three questions you can ask to determine if something is state?
  1. Is it passed in from a parent via props? If so, it probably isn’t state.
  2. Does it remain unchanged over time? If so, it probably isn’t state.
  3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
- How can you identify where state needs to live?
  - Identify what the state is altering. Find a common parent component, or create a new higher component. 

### [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

- What is a “higher-order function”?
   -Functions that operate on other functions, either by taking them as arguments or by returning them.
- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - It is returning m if m is greater than n.
- Explain how either map or reduce operates, with regards to higher-order functions.
  - These methods go through an array and applies a function to all of its elements, then build a new array from the returned values.