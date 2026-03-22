# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for all interactive elements
- Experience a smooth fade-in animation on page load
- Navigate accessible content using screen readers (ARIA support)

### Screenshot

![Design preview](./screenshots/desktop-preview.jpg)

### Links

- Solution URL: [https://github.com/dreamer111111/Frontend-Mentor-NFT-preview-card-component]
- Live Site URL: [https://nft-card-frontendmentor1.netlify.app/]

## My process

### Built with

- **Semantic HTML5** - Using `<article>`, `<header>`, and `<footer>` for better SEO and accessibility.
- **CSS Custom Properties** - Centralized design tokens for colors and typography.
- **Flexbox & Grid** - For precise alignment and centering.
- **Logical Properties** - Using `margin-block` and `padding-inline` for modern, internationalized spacing.
- **A11y (Accessibility)** - Including `sr-only` labels for screen readers and `prefers-reduced-motion` support.

### What I learned

Coming from a JavaScript background, I focused on making the CSS more "logical." I learned how to use absolute positioning context to create an image overlay that matches the image dimensions perfectly without "bleeding" into the rest of the card.

I also mastered the use of **Logical Properties**, which feel more programmatic than physical directions:

```css
/* Using logical properties for vertical spacing */
.nft-title {
  margin-block-end: 1rem;
}

/* Ensuring the overlay stays within the image bounds */
.nft-image-container {
  position: relative;
  display: flex;
}