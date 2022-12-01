# Code 201 Reading Notes

[Class 1](https://melanie-johnston.github.io/reading-notes/201/class1) -
[Class 2](https://melanie-johnston.github.io/reading-notes/201/class2) -
[Class 3](https://melanie-johnston.github.io/reading-notes/201/class3) -
[Class 4](https://melanie-johnston.github.io/reading-notes/201/class4) -
[Class 5](https://melanie-johnston.github.io/reading-notes/201/class5) -
[Class 6](https://melanie-johnston.github.io/reading-notes/201/class6) -
[Class 7](https://melanie-johnston.github.io/reading-notes/201/class7) -
[Class 8](https://melanie-johnston.github.io/reading-notes/201/class8) -
[Class 9](https://melanie-johnston.github.io/reading-notes/201/class9) -
[Class 10](https://melanie-johnston.github.io/reading-notes/201/class10) -
[Class 11](https://melanie-johnston.github.io/reading-notes/201/class11) -
[Class 12](https://melanie-johnston.github.io/reading-notes/201/class12) -
[Class 13](https://melanie-johnston.github.io/reading-notes/201/class13) -
[Class 14](https://melanie-johnston.github.io/reading-notes/201/class14) -
[Class 15](https://melanie-johnston.github.io/reading-notes/201/class15)

---

## Class 5 Notes

### HTML

Making wesbites accessible is an important part of web development. One of those ways is to include an `alt` attribute on images. It helps to be descriptive for those using screen readers. It's also a great tool to test if your images are loading correctly (and which one is which).

    <img src="puppy.jpg" alt="Puppy rolling in snow" />

There is also the option to include the `figure` attribute. This encases a photo and caption in a container.
    <figure>
      <img
        src="puppy.jpg"
        alt="Puppy rolling in snow"
        width="400"
        height="341" />

      <figcaption>
        Our puppy, Spot, experiencing snow for the first time.
      </figcaption>
    </figure>

There are several image file types. A couple common ones are `gif` and `svg`. Gif is a good choice for simple images and animations. Svg is ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes.

For screenshots, PNG is the most common or lossless WebP.

### CSS

At a fundamental level, the `color` property defines the foreground color of an HTML element's content and the `background-color` property defines the element's background color. These can be used on just about any element. Imagine you are making a "Happy Birthday" poster. The `background-color` will be the poster color. Whatever markers/paint you use to write "Happy Birthday" will be the `color`.

Color on a website can make a world of difference, but don't go crazy with too many colors. If I were to bring color to a blog website, I'd stick with a black/white scale and then bring in one pop of color. Let's choose orange - I would change nav button colors to orange, and maybe create a hover color change effect on the blog posts.  

There are only a certain number of fonts that are generally available across all systems and can therefore be used without much worry. These are the so-called web safe fonts. You can also font stack so the browser has multiple fonts to choose from. These are called `font-family`.  You can also link a free font (like from google fonts).

There are several attributes that affect text. To change how your text looks, `font-size` changes the size, `font-weight` changes the thickness (normal, bold, extra-bold), and `font-style` turns italic on/off.

Text alignment can be used to control how text is aligned in it's container.

    h1 {
       text-align: center;
    }

You can also add letter and word spacing.
    h1 {
       letter-spacing: 4px;
       word-spacing: 4px;
    }

#### Things I want to know more about

Best ways to use font properties for making things look nicec