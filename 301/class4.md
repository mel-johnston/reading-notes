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

## Class 4 Notes - React and Forms

### [React Docs - Forms](https://reactjs.org/docs/forms.html)

- What is a ‘Controlled Component’?
  - Controlled Components are those in which form’s data is handled by the component’s state. It takes its current value through props and makes changes through callbacks like onClick,onChange, etc. 
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  - Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.
- How do we target what the user is entering if we have an event handler on an input field?
  - handleChange(event) this will update when a user chooses an input

### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- Why would we use a ternary operator?
  - It's much shorter than an if/else statement and the condition will be true/false 
- Rewrite the following statement using a ternary statement:

      if(x===y){
        console.log(true);
      } else {
        console.log(false);
      }

  - This becomes:

      x === y ? console.log(true) : console.log(false)

