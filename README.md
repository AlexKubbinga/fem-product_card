# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Recreate the product card component as seen on frontend mentor. The card component should be responsive for both web and mobile.

### Solution site

[My Product Gard Github Pages Site](https://alexkubbinga.github.io/fem-product_card/)

### Screenshot

![](./desktop_final.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project was a good refresher on structuring a page into different div components. I created a product card div to hold all of the details in the card. This was then separated into product-info, price-details and the add-to-cart section.

Centering items was the hardest thing and this required relearning how to use flex box and center items.
```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```
I learned how to render different images based on the screen size using the <picture> tag.
```html
<picture>
<!-- desktop image -->
 <source srcset="images/image-product-desktop.jpg"" media="(min-width: 1024px)">
 <!-- mobile image -->
 <img src="images/image-product-mobile.jpg", alt="Gabrielle Essence Eau de Parfum" class="product-image">
</picture>
```





