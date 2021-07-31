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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

[design/joricky-stat-preview.png]

### Links

- Solution URL: [https://github.com/joricky91/Stats-preview-card-component]
- Live Site URL: [https://joricky91-stats-preview.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```
:root{
    --very-dark-blue: hsl(233, 47%, 7%);
    --dark-desaturated-blue: hsl(244, 38%, 16%);
    --soft-violet: hsl(277, 64%, 61%);
    --white: hsl(0, 0%, 100%);
    --slightly-transparent-white1: hsla(0, 0%, 100%, 0.75);
    --slightly-transparent-white2: hsla(0, 0%, 100%, 0.6);
}
I learned many about the use of variables in CSS. This really helps when I want to use the same color I just need to type the variable, not scrolling up and find what the hex or rgba of the color i want to use.

.container .picture .overlay{
    background-color: hsl(277, 64%, 61%, 0.7);
    height: 400px;
    border-radius: 10px 10px 0 0;
}
This also help me to better understand how to implement overlay and set opacity of the overlay.
```

### Continued development

I want to focus on media queries in the future, because I still don't fully understand the implementation of media query. Also, want to focus on targeting elements in CSS, often I typed the wrong class or tag when I want to target and style some elements.

### Useful resources

- [https://www.youtube.com/watch?v=2tlbKm8_4mg&t=2642s] - This helped me a lot, especially while I designing the mobile version of this challenge because I confused a bit when targeting class. If you're stuck or confused, you can check this channel.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/joricky91]
- Twitter - [https://twitter.com/joricky91]

## Acknowledgments

Special thanks to tsbsankara's Youtube Channel, this help me so much when I design the mobile version of the challenge. Thank you for the solution in the video you created.

