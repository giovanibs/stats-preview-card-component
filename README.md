# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#responsive-screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Responsive Screenshots

- Desktop Preview:

![](images/desktop-preview.png)

- Tablet Preview:

![](images/tablet-preview.png)

- Mobile Preview:

![](images/mobile-preview.png)


### Links

- Live Site URL: [https://giovanibulian.github.io/stats-preview-card-component/](https://giovanibulian.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries for different devices


### What I learned

I've learned how to use the srcset and media attributes for images to optmize network usage. The code below was used to switch between 2 image files depending on the device's screen size:

```html
<picture id="img-container">
      <source media="(min-width: 769px)" srcset="images/image-header-desktop.jpg">
      <source media="(max-width: 768px)" srcset="images/image-header-mobile.jpg">
      <img id="card-img" src="images/image-header-desktop.jpg" alt="women working in the office">
   </picture>
```

### Continued development

- Start using Mobile First approach.
- Learn more about semantics and  accessibility.
- Learn further about srcset.


## Author

- Website - [Giovani Bulian Simioni](https://github.com/giovanibulian)