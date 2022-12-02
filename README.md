# Make It Real - QR code component

This is a solution to the fourth HTML/CSS project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Solution Screenshot](#Solution-Screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Students should be able to:

- Design a price component as close as the screenshot picture of the project.

### Solution Screenshot

![Fullsize screen](./desktop-ss.png)
![Mobile screen size](./mobile-ss.png)

## My process

### Built with

- CSS custom properties
- Flexbox
- Grid
- Media Queries (Breakpoint 500px, 800px)
- Boxshadow property

### What I learned

We learned how to use properties such as Grid and Media Queries for appropiate price components positioning according to the window size.

```css
#container {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: repeat(3, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  box-shadow: 6px 6px 10px 3px rgb(0 0 0 / 10%);
  font-family: "Karla", sans-serif;
}
```

### Continued development

It will be nice to use React to create the same layout.

### Useful resources

- [Flexbox tutorial](https://www.youtube.com/watch?v=tXIhdp5R7sc) - This helped me figuring out how to use Flexbox properties.
- [Media queries](https://youtu.be/sd16e11blHI) - This is an amazing tutorial for media queries basic concepts.
- [Boxshadow property](https://youtu.be/1aIcnXaEjmQ) - This is an amazing tutorial for Boxshadow property basic concepts.
- [Grid property](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout) - This is an amazing grid property resourse.

## Author

- Github - [Juan Velasco](https://github.com/juandiegovelsol)
- Github - [Moises](https://github.com/juandiegovelsol)
- Github - [Felipe](https://github.com/juandiegovelsol)

## Acknowledgments

Kudos to our friends and mentors: Sergio Jaramilo and Daniel Espitia.
