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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop](./screenshots/Screenshot%202022-12-02%20at%2021-04-23%20Frontend%20Mentor%203-column%20preview%20card%20component.png)

![mobile](./screenshots/Screenshot%202022-12-02%20at%2021-06-27%20Frontend%20Mentor%203-column%20preview%20card%20component.png)

### Links

- Solution URL: [Solution URL here](https://github.com/AlanLopRey/3-column-preview-card-component-main)
- Live Site URL: [Live site URL here](https://alanloprey.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS pre-processor
- [BEM metodology](https://getbem.com/) - Block Element Modifier metodology

### What I learned

this proyect was pretty easy in a certain way, using the BEM metodology I was able of writte les CSS code in the section part putting two classes in one section one thing that BEM helps to do it, and also have more control when I put the diferents colors and styles for each card by follow this metodolgy, maybe I found some difficulties when I try to put the different styles for each button

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
@media screen and (min-width: 1440px) {
  body {
    justify-content: center;
  }

.sedan__button:hover {
  background-color: $Bright-orange;
}
.sedan__button:hover .sedan__button--span {
  color: $Very-light-gray;
}

.suv__button:hover {
  background-color: $Dark-cyan;
}
.suv__button:hover .suv__button--span {
  color: $Very-light-gray;
}

.luxury__button:hover {
  background-color: $Very-dark-cyan;
}
.luxury__button:hover .luxury__button--span {
  color: $Very-light-gray;
}
```

### Continued development

Now I felt more comfortable using SASS but I know that I need to keep develop the use of this tool, maybe I could use less code using mixings in the part of the media query and the buttons but It is something i still need figure out how to do it, beside that this was a pretty fun challenge

### Useful resources

- [piccalil](https://piccalil.li/blog/a-modern-css-reset/) - This page helped me to get a better reset of my code

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

I thank [@correlucas](https://www.frontendmentor.io/profile/correlucas) for all the feedback in previous challenge as well for all the dedication giving advices for most of the community thanks lucas
