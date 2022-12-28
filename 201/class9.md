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

## Class 9 Notes - Forms and JS Events

### HTML Forms

Why are forms so important in web development?

- Web forms are one of the main points of interaction between a user and a website or application.
- Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way.

When designing a form, keep it simple and stay focused: ask only for the data you absolutely need.

List 5 form elements and explain their importance.
  `form`  formally defines a form and attributes that determine its behavior
  `fieldset` can create groups of widgets, you can label by using a:
  `legend` which formally describes the purpose of the `fieldset`
  `label` is important to include if you want your forms accessible
  `button` can be used in forms to submit data


### JS Events

Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them. To explain to someone, if I press the buttons on an oven to 350 degrees, the oven's action is to start heating up so it can reach that temperature.

When using the addEventListener() method, what 2 arguments will you need to provide?

- the name of the event
- a function to handle the event

Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.

Event bubbling describes how the browser handles events targeted at nested elements. We describe this by saying that the event bubbles up from the innermost element that was clicked.

#### Things I want to know more about

Fun ways to implement forms