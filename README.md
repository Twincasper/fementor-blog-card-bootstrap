# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%202024-10-10%20at%2011.15.10 AM.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/blog-preview-card-primarily-using-flexbox-and-css-variables-6W1yNERPbz)
- Live Site URL: [Github pages deployment](https://twincasper.github.io/fementor-blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I feel like I'm getting better at doing stuff like this. Setting up a div, and centering it's items within it without over engineering the code. Also, this is the first time in a while I've used CSS variables based on a style guide and it feels like a nice workflow to just use the same variables over and over, rather than hex codes.

```css
body {
  font-family: 'Figtree';
  background-color: var(--color-yellow);
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0;
}

#card {
  display: flex;
  width: 24rem;
  padding: var(--spacing-200);
  flex-direction: column;
  align-items: flex-start;
  gap: var(--spacing-200);
  border-radius: 1.25rem;
  border: 1px solid var(--color-gray-950);
  background: var(--color-white);
  box-shadow: 8px 8px 0px 0px #000;
}
```

### Continued development
I want to challenge myself to start using grid instead of flex for everything, just to test and strengthen my understanding of it.

## Author

- Frontend Mentor - [@Twincasper](https://www.frontendmentor.io/profile/Twincasper)


## Acknowledgments

Many thanks to the other people in the room making idle noise while I was working on this. It actually helps me.

