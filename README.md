# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/ScreenShotDesktop.png)
![](./images/ScreenShotMobile.png)

### Links

- Solution URL: [Portfolio](https://gelatodigital.com/portfolio)
- Live Site URL: [rodrigos-huddle-landing-page-single-introductory-section](https://rodrigos-huddle-landing-page-single-introductory-section.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Font awesome goes inside of other parent containers, and you customize the size and color from there

```html
      <span>
        <i class="fa fa-instagram icon"></i>
      </span>
```

Sometimes you can fit the background image just perfectly, but other times it is better to just stop worrying about pixel perfect and move on. Speed conquers all in this game
```css
    .picture{
        background-image: url('./images/illustration-mockups.svg');
        background-size: contain;
        background-repeat: no-repeat;
        min-height: 70vh;
    }
```

### Continued development

Still working around svgs. Used several on this project but avoided any time I could. Maybe one day they'll com ein handy, but not today.

### Useful resources

- [Font Awesome](https://fontawesome.com/)
- [background image size](https://www.freecodecamp.org/news/css-full-page-background-image-tutorial/)

## Author

- Website - [Rodrigo Barbosa](https://www.gelatodigital.com)
- Frontend Mentor - [@Rod-Barbosa](https://www.frontendmentor.io/profile/Rod-Barbosa)
