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

## Class 2 Notes - React and Component-Based Architecture

### React lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - render
- What is the very first thing to happen in the lifecycle of React?
  - constructor
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  - constructor
  - render
  - React Updates
  - componentDidMount
  - componentWillUnmount
- What does componentDidMount do?
  - This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

### React State Vs Props

- What types of things can you pass in the props?
  - Things that you want your component to render, things you want to display to the user
- What is the big difference between props and state?
  - State is handled and updated inside a component, props are handled outside and passed to the component.
- When do we re-render our application?
  - State is used to re-render when a user's input dictates
- What are some examples of things that we could store in state?
  - A counter - something that will be updated

#### Things I want to know more about

More examples of state vs props