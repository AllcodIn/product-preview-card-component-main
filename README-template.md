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



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.png)


### Links

- Solution URL: [product-preview-card-component-main]()
- Live Site URL: [product-preview-card-component-main](https://allcodin.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This code allow to put a default image and specify another image according to the screen size. 
    "very useful for responsive dessign"

```html
  <picture>
    <source srcset="./images/image-product-desktop.jpg" media="(min-width: 48em)">
    <img src="./images/image-product-mobile.jpg" class="card-img" alt="image-product">
  </picture>
```


## Author

- GitHub - [AllcodIn](https://github.com/AllcodIn/product-preview-card-component-main.git)
- Frontend Mentor - [@AllcodIn](https://www.frontendmentor.io/profile/AllcodIn)

