# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202026-02-03%20at%2014-21-15%20Frontend%20Mentor%20Order%20summary%20card.png)

### Links

- Solution URL: [frontendmentor.io/challenges/order-summary-component-QlPmajDUj](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)
- Live Site URL: [michael-andreas.github.io/order-summary-component/](https://michael-andreas.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Different background images depending on screen size:

```css
.bg-pattern-mobile {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  z-index: -1;
}

.bg-pattern-desktop {
  display: none;
}

@media (min-width: 640px) {
  .bg-pattern-mobile {
    display: none;
  }

  .bg-pattern-desktop {
    display: block;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    z-index: -1;
  }
}
```

## Author

- Website - [michaelandreas.de](https://michaelandreas.de)
- Frontend Mentor - [@Michael-Andreas](https://www.frontendmentor.io/profile/Michael-Andreas)
