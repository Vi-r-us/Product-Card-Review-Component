# Product Preview Card Component

I created the Product Preview Card Component, featuring a modern-looking UI design that is responsive to all screen sizes. This project was developed as part of the [Frontend Mentor challenge](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). To achieve responsiveness, I utilized grid and flexbox layouts, supplemented with media queries.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

One of the challenges I faced during this project was implementing different images for desktop and mobile views. To address this, I employed the `<picture>` tag with the `<source>` tag, utilizing `srcset` and media attributes to set images accordingly.

### Screenshot

Desktop Design            |  Mobile Design 
:-------------------------:|:-------------------------:
![](./design/desktop-design.jpg)  |  ![](./design/mobile-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Vi-r-us/Product-Card-Review-Component)
- Live Site URL: [Deployed on Github pages](https://vi-r-us.github.io/Product-Card-Review-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS (Grid, Flexbox, Media Queries)

### What I learned

This project provided valuable experience in front-end development, especially in achieving responsive design using grid, flexbox, and media queries. Overcoming image challenges with the `<picture>` and `<source>` tags expanded my understanding of responsive web design.

```html
  <picture class="product__img">
    <source srcset="images/image-product-desktop.jpg" 
      media="(min-width: 620px)">
    <img src="images/image-product-mobile.jpg" 
      alt="Perfume Image">
  </picture >
```

### Useful resources

- [Kevin Powell's video on the same](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=1714s) - This helped me learn to use picture and srcset.
- [My Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - Whenever I start a new project, I use Joshw Comeau's CSS presets.

## Author

- Github - [vi-r-us](https://github.com/Vi-r-us)
- Frontend Mentor - [@Vi-r-us](https://www.frontendmentor.io/profile/Vi-r-us)
