# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)




## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Links

- Live Site URL: [Add live site URL here](https://67e405ad91dbd733234dd3d8--kaleidoscopic-palmier-e44c9b.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
.laptop-img,
.mobile-img {
  max-width: 100%;
  height: auto;
  display: none;
}

/* Show laptop image on screens wider than 700px */
@media screen and (min-width: 700px) {
  .laptop-img {
    display: block;
    width: 100%;
    height: 100%;
    max-width: 600px;
    /* Adjust the size */
  }
}

h2 {
  font-size: 2em;
  font-family: var(--secondary);
}

/* Show mobile image on screens smaller than 700px*/
@media screen and (max-width: 699px) {
  .mobile-img {
    display: block;
    width: 100%;
    height: 100%;
    max-width: 500px;
    /* Adjust the size */
  }
}

@media (max-width: 740px) {
  .product-card {
    flex-direction: column;
  }

  .product-image,
  .product-description {
    flex: 1;
  }
}

```

### Useful resources

- [(https://courses.kevinpowell.co/] - This helped me for the media queries. 

## Author
- Frontend Mentor - [@Til-da](https://www.frontendmentor.io/profile/Til-da)
