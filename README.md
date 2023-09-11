# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [Add live site URL here](https://chartdesign.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use the css "overflow: hidden" to make the image and the content div conform to the border radius.
I learned the use to the "srcset" in html to switch images according to screen size.

```html
<picture class="product-img">
  <source
    srcset="images/image-product-desktop.jpg"
    media="(min-width: 600px)"
  />
  <img src="images/image-product-mobile.jpg" alt="perfume" />
</picture>
```

```css
.card {
  display: grid;
  background-color: var(--clr-neutral-100);
  border-radius: 0.5rem;
  overflow: hidden;
  max-width: 375px;
}
```

## Author

Curtis Hartshorne

## Acknowledgments

Kevin Powell's youTube channel:
(https://www.youtube.com/watch?v=B2WL6KkqhLQ&list=PL4-IK0AVhVjPKyc9UTHzx9xUnZYTGGi2b&ab_channel=KevinPowell)
