# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/min4899/Frontend-Mentor-Stats-Preview-Card-Component)
- Live Site URL: [Github Pages](https://min4899.github.io/Frontend-Mentor-Stats-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Finally understood how CSS min and max functions work thanks to the Web Dev Simplified video. Min function just takes a group of measurement and applies the smallest unit. Max applies the largest unit. I applied the min function for resizing the card image when screen gets smaller. If the screen is large enough, 540px would be used since it'd be smaller than 46vw. Once screen is smaller enough, 46vw would be smaller so it'd be used instead.

```css
.card-image-with-overlay {
  position: relative;
  display: grid;
  place-items: center;
  width: min(46vw, 540px);
}
```

### Continued development

So far, I've been working on card components just centered on the screen. For next challenges, I'd like to try creating a full pages.

### Useful resources

- [CSS Min/Max Functions Are Incredible](https://www.youtube.com/watch?v=MHN0d8R_swc&ab_channel=WebDevSimplified) - Simple, easy to understand explanation of how CSS min and max.functions work.
- [StackOverflow - How to make in CSS an overlay over an image?](https://stackoverflow.com/questions/21086385/how-to-make-in-css-an-overlay-over-an-image) - Simple solution for the purple overlay over the card image.
- [imagekit.io - CSS image overlay](https://imagekit.io/blog/css-image-overlay/) - A more detailed explanation of how to create overlays. Tried to use the image gradient overlay effect, but didn't work. Used the overlay using vanilla div element option.

## Author

- GitHub - [Minwoo Soh](https://github.com/min4899)
- Frontend Mentor - [@min4899](https://www.frontendmentor.io/profile/min4899)