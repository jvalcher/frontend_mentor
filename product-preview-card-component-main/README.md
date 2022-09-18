# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Desktop Screenshot](#desktop-screenshot)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Desktop Screenshot

<img src="desktop.png" alt="desktop version" width="500px"/>


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that you can wrap a button div inside of an anchor to make the whole thing clickable.

```html
<a href="#" class="add-link">
  <div class="add-button">
    <svg class="add-icon" width="15" ... ></svg>
    <p class="add-text">Add to Cart</p>
  </div>
</a>
```
```css
.add-link {
  text-decoration: none;
}
```

## Author

- Frontend Mentor - [@jvalcher](https://www.frontendmentor.io/profile/jvalcher)
