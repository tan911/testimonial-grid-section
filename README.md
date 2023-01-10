# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot/Solution.png)

### Links

- Solution URL: [Code](https://github.com/tan911/testimonial-grid-section)
- Live Site URL: [Live site](https://tan911.github.io/testimonial-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass/scss
- BEM (naming)

### What I learned

Although this application doesn't have a particularly difficult layout, I had a fun day making it. It was a good opportunity for me to practice using a grid system.
I've discovered something quite helpful that I may use for my upcoming challenge, which is including the proper semantics when producing my HTML.

This is my code, which has multiple divs. div is merely a container.

```html
<div>
  <img />
  <div>
    <h2>text</h2>
    <p>text</p>
    <p></p>
  </div>
  <div></div>
</div>
```

and to improve the content of my document, I have to write the right elements into it

```html
<figure>
  <figcaption>
    <img />
  </figcaption>
  <blockquote></blockquote>
</figure>
```

This is being done with the intention of being able to explain how the structure and content relate to one another.

### Useful resources

- [CSS grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Author

- Website - [Jovan Lanutan](https://portfolio-tan911.vercel.app/)
- Frontend Mentor - [@tan](https://www.frontendmentor.io/profile/tan911)
