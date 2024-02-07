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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Result Preview](images/Result-preview%20Frontend%20Mentor%203-column%20preview%20card%20component.png)

### Links

- GitHub Repository URL: [Add solution URL here](https://your-solution-url.com)
- GitHub Page URL: [GitHub Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

For this challenge, I prefer using CSS Grid to familiarize myself with setting Grid properties, particularly sizing, as it has been one of the more challenging aspects. Thankfully, Chrome developer tools prove invaluable in visualizing the perfect card dimensions.

I thoroughly enjoyed experimenting and solving the puzzle of grid setup.

Another exciting aspect is configuring button hover properties. In this instance, it's all about defining the background color, which should disappear upon hovering, while ensuring the font color matches the card's background when not hovered over.

I'm using the grid-template-columns property set to repeat(auto-fill, 250px) to ensure that the cards wrap dynamically based on the screen size.

```css
.container {
  display: grid;
  grid-template-columns: repeat(auto-fill, 250px);
  grid-auto-flow: dense;
  margin: 2vw 8vh;
}
```

To make the background color of the button disappear upon hovering, I'm utilizing the transparent property.

```css
button:hover {
  cursor: pointer;
  color: white;
  background-color: transparent;
  border: 2px solid white;
}
```

### Continued development

One critical area for improvement is a deeper understanding of grid properties and the appropriate unit of measurements for creating a responsive page. Without a solid grasp of these fundamental concepts, the development process can be exceedingly challenging for developers. Delving into the intricacies of sizing within CSS grids, along with mastering units like percentages, ems, rems, and viewport-relative units, is essential for crafting layouts that seamlessly adapt to various screen sizes and devices. Investing time in learning these foundational principles will undoubtedly streamline the development workflow and enhance the quality of the final product.

## Author

- Website - [Ano Jumisa](https://www.anojumisa.com)
- Frontend Mentor - [@anojumisa](https://www.frontendmentor.io/profile/anojumisa)
- Twitter - [@anojumisa](https://www.twitter.com/anojumisa)
