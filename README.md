# Frontend Mentor - Huddle landing page with single introductory section solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: [https://tomasscerbak.github.io/status-card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I've learned GRID and some features how to work with grid layout and reverse positions

```css
@media screen and (min-width: 768px) {
  .card {
    grid-template-columns: 1fr 1fr;
    margin: 10rem 8rem;
  }
  .item-1 {
    grid-column: 2 / -1;
    grid-row: 1 / -1;
  }
  .item-2 {
    grid-column: 1 / 2;
    grid-row: 1 / -1;
  }
```
### Continued development

there are still many option and usages how to work with GRID. I will continue learing FLEX and GRID as these are very important tools for webpage layout

## Author

- Website - [Tomas Scerbak](https://tomasscerbak.github.io/tomas-scerbak-portfolio/)
- Frontend Mentor - [@Potato
