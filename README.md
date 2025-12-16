# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

!

### Links

- Solution URL: Add solution URL here
- Live Site URL: Add live site URL here

## My process

### Built with

- Semantic HTML5 markup
- Sass/SCSS for modular and nested styles
- Flexbox for layout
- Mobile-first workflow
- Vanilla JavaScript for form validation

### What I learned

This project was a great exercise in creating a responsive layout that changes significantly between mobile and desktop. One interesting part was layering a background color, a gradient, and an SVG background pattern and making them work together.

A specific challenge was styling the form input and button to appear as a single, cohesive unit on desktop, especially ensuring their heights matched perfectly and the button overlapped the input field correctly.

```scss
.main__text-container__input {
  display: flex;
  flex-direction: row;
  align-items: center;

  input {
    border: solid 1px $primary-color;
    border-radius: 2rem;
    padding: 1rem 2rem;
    width: 75%;
    height: 3rem;
  }

  button {
    position: relative;
    right: 50px; // Overlaps the input
    height: 3rem; // Matches input height
    /* ... other styles */
  }
}
```

### Continued development

In future projects, I want to focus more on accessibility from the start, such as adding `aria-live` regions for form error messages to ensure they are announced by screen readers. I also plan to continue refining my Sass architecture for even larger projects.

## Author

- Frontend Mentor - @yourusername
- GitHub - Your Name
