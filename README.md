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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The challenge was to build out a product preview card component and get it looking as close to the design as possible. Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Desktop Screenshot

<img src="./finished-design/desktop.jpg" width="100%">
  
### Mobile Screenshot
<img src="./finished-design/mobile.png" width="40%">

### Links

- Solution URL: [FEM Product Preview Card](https://ms-fem-product-preview.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This was the first time I used the ```srcset``` property for an image. It helps the site load faster on mobile sites, but I did find that when resizing the site to check responsiveness I had to reload the site to make sure the right image was being loaded.

```html
<img class="card__image" srcset="images\image-product-mobile.jpg 375w, images\image-product-desktop.jpg, 686w"
      sizes="(max-width: 600px) 375px, 686px" alt="CHANEL Gabrielle Essence Eau De Parfum"
      src="images\image-product-desktop.jpg">
```

I also used SASS class concatenation to create classes with a high degree of specificity while maintaining readable and logical code.
```css
.card {
  &__image {}

  &__content {
    &__headers {}
  }
}
```

### Continued development

This was a fun project, and having a prebuilt card that I can include in future projects will surely be useful. I've built it in a way that by changing a few parameters, it could easily be used in another project.

### Useful resources

- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - MDN Is alway a great resource, and this helped me figure out how to use ```srcset``` while working on this project..
- [SCSS "&"  explained](https://medium.com/the-crazy-coder/what-scss-means-e448e2ac98d3) - This is a great article which which explains how to use the ampersand in SCSS.

## Author

<!-- - Website - [Mich Stacey](https://www.your-site.com) -->
- Twitter - [@Mich_Codes](https://twitter.com/Mich_Codes)
- Frontend Mentor - [@mich-codes-sa](https://www.frontendmentor.io/profile/mich-codes-sa)