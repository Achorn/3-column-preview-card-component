# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![Finished web design](./images/web-finished.png)
![Finished web design](./images/mobile-finished.png)

### Links

- Solution URL: [Front End Mentor](https://www.frontendmentor.io/solutions/flex-box-and-media-queries-vRqEfmg8-)
- Live Site URL: [achorn.github.io/3-column-preview-card-component/](https://achorn.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Web-first workflow

### What I learned

Used this challenge to reinforce fundamental practices for html and css. I also used flex-grow on the card componenents in order to keep the cards uniform and to have the button on the bottom of the card.

```css
.card {
  display: flex;
  flex-direction: column;
  padding: 55px;
  height: 370px;
}
/* paragraph fills the majority of the card */
p {
  color: hsla(0, 0%, 100%, 0.75);
  line-height: 2;
  flex-grow: 4;
}
```

### Continued development

My focus with this beginner projects is to slowely add more tools to my web dev toolbox. I already know flex box but to take the time to find the right way to use these tools is what im working towards

### Useful resources

- [FlexBox Complete Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This resource is always helpful when you forget some properties.

## Author

- Website - [Joshua Achorn](https://achorn.github.io/)
- Frontend Mentor - [@Achorn](https://www.frontendmentor.io/profile/Achorn)
- Twitter - [@achorn91338214](https://twitter.com/achorn91338214)

## Acknowledgments

No acknoledgements for this challenge
