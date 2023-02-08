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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Mobile Version Result](./mobile-completed.png)
![Desktop Version Result](./desktop-completed.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This is my firt time using more grid than flex for layout reasons. Thats becouse I take the time to really grasp the difference between the two displays.
Now that I know what each one does in more depth I'm not constantly figthing against the styles, I love that

Learned how to change images for different displays with the picture and source tag

```html
<picture class="product-card__image">
  <source
    srcset="images/image-product-desktop.jpg"
    media="(min-width: 600px)"
  />
  <img
    src="/images/image-product-mobile.jpg"
    alt="Grabrielle chanel perfume bottle lying down flat on a table with weed on top and bottom"
  />
</picture>
```

I learned another wat to add a icon next to text

```css
.button[data-icon="shopping-cart"]::before {
  content: "";
  width: 15px;
  height: 16px;
  background-image: url("/images/icon-cart.svg");
  margin-right: 0.5rem;
}
```

### Useful resources

- [Kevin Powell](https://www.youtube.com/@KevinPowell) - This was my main source of knowledge speaking about css

## Author

- Website - [Elian Avalos]()
- Frontend Mentor - [@Elian-A](https://www.frontendmentor.io/profile/Elian-A)
