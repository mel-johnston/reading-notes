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

## Class 11 Notes - Video, Audio, Grid, & Responsive Images

### Video and Audio Content

Video and audio started out very simple and primitive. It has evovled tremendously over the last 20 years. Not only are things smoother and higher quality, but easier to code and embed. 

The `video` element allows you to embed a video very easily. The `src` (source) attribute contains a path to the video you want to embed. Users must be able to control video and audio playback. You can do this through the use of `controls` which include the browser's own control interface, or build your own through JavaScript APIs. 

The paragraph inside the `video` tags is fallball content. This will be displayed if the browser accessing the page doesn't support the `video` element, allowing us to provide a fallback for older browsers.



### A Complete Guide To Grid

CSS Grid Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. 

Flexbox is one-directional and has different uses. Flexbox and Grid can be used together and work well. 

- Grid container: the element on which `display: grid` is applied. It's the direct parent of all the grid items.
- Grid item: the childen of the grid container.
- Grid line: the dividing lines that make up the structure of the grid.
- Grid cel: the space between two adjcent row and two adjacent column grid lines. 
- Grid track: the space between two adjacent grid lines, basically the columns or rows of the grid.
- Grid area: the total space surrounded by four grid lines.

### Responsive Images

Choosing the appropiate resolution and size of an image will reduce bandwidth and enhace user experience.

- `srcset` defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.
- `sizes` defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true

When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset.

#### Things I want to know more about

- Will we be using video elements often? Or are APIs more common?