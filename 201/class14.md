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

## Class 14 Notes - CSS

### CSS Transforms

What does a CSS transform allow the developer to do to an element?

- Transforms can be applied on a 2D or 3D level.
- Transform rotate(deg) will rotate an element from 0-360 degrees.
- Transform scale() will change the size of an element (shrink or grow).
- Transform translateX/Y() will change the relative position of the element.
- Transform skewX/Y() will distort elements on the horizontal/vertical axis or both. 

Provide an example of a transform and how you could see that being used on a website.

- Transform is a great way to make buttons or clickable items more interactive. I have used the following code with a button before. It will make the button grow 1.2x it's size when hovered over. Adding the `transition` property to the base element will make the transition apply to both the hovering over, and moving away from the button.

    button{
      transition: transform .4s;
    }

    button:hover{
        transform: scale(1.2);
      }

### CSS Transitions & Animations

What does a CSS transition allow the developer to do to an element?

- Transition allows you to change the state of an element and apply certain properties to the transition.
- Some examples of this include the timing (like slowing down a hover effect) and duration (how long the change takes overall).
- Transition can only be used on elements that have an identifiable halfway point: colors, spacing, height, width, shadows, etc.

How does a CSS animation differ from a CSS transition?

- Animations have multiple states, whereas transitions only have two.
- Animations can have changes at multiple points like 0%, 25%, 50%, 75% and so on.

What are some benefits to using CSS transitions on websites?

- Transitions make the user's experience more enjoyable, increase interactivity, and overall make your website look and feel better.

How this topic fit in with your long-term goals?

- My long (and short) term goal is to be really good at CSS and make websites look beautiful. These are some examples of simple but very effective ways of leveling up websites.

#### Things I want to know more about

Simple animations to make a website feel more interactive