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

## Class 1 Notes - Passing Functions as Props

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?
  - Map returns a new array with whatever you've selected
- If I want to loop through an array and display each value in JSX, how do I do that in React?
  - Loop through an array, return the values as HTML elements, such as `<li>`.
- Each list item needs a unique key.
- What is the purpose of a key?
  - Keys help React identify which items have changed, are added, or are removed.

### [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?
  - The spread operator expands an iterable object, usually an array, though it can be used on any interable, including a string.
- List 4 things that the spread operator can do.
  - copy an array
  - use math functions
  - adding to state in React
  - combining objects
- Give an example of using the spread operator to combine two arrays.
      
      const arr = [1,2,3]
      const arr2 = [4,5,6]
      const arr3 = [...arr1,...arr2]

- Give an example of using the spread operator to add a new item to an array.

      const yellowHeart = [💛]
      const allHearts = [💚, 💙, ...yellowHeart]

- Give an example of using the spread operator to combine two objects into one.

      const yellowHeart = {yellow: 💛}
      const allHearts = {green: 💚, blue: 💙, ...yellowHeart}

### [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU&ab_channel=SteveGriffith-Prof3ssorSt3v3)

- In the video, what is the first step that the developer does to pass functions between components?
  - He passes the function to the child as a prop
- In your own words, what does the increment function do?
  - It changes the hasChanged to true and updates a span on the component and increases the counter
- How can you pass a method from a parent component into a child component?
  - You include it in the child as a prop
- How does the child component invoke a method that was passed to it from a parent component?
  - It is called as a prop: `this.props.example`

#### Things I want to know more about

I just want to see more examples of props and state.