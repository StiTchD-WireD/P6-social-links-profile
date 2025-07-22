# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

Mobile:

![assets/images/Screenshot Social links profile Mobile.png](assets/images/Screenshot%20Social%20links%20profile%20Mobile.png)

Browser:

![assets/images/Screenshot Social links profile Browser.png](assets/images/Screenshot%20Social%20links%20profile%20Browser.png)


### Links

- Solution URL: [GitHub](https://github.com/StiTchD-WireD/P6-social-links-profile)
- Live Site URL: [GitHub Pages](https://stitchd-wired.github.io/P6-social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- hover vs focus

- Using <button> in and anchor tag is problematic for ARIA, it creates a double focus when using the tab key resulting in needing to press tab twice to go to the next option. It is better to style an anchor as a button using CSS.

```css
.social-links {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 90%;
}


.social-links > a {
  width: 100%;
  padding: 1em;
  border-radius: .5em;
  background-color: var(--Grey-700);

  text-decoration: none;
  color: var(--White);
  font-size: 1.1em;
  font-weight: 600;
  text-align: center;
  cursor: pointer;
  margin-top: .8em;
}

a:hover,
a:focus {
  background-color: var(--Green);
  color: var(--Grey-800);
}
```

### Continued development

- Java Script

## Author

- Frontend Mentor - [@StiTchD-WireD](https://www.frontendmentor.io/profile/StiTchD-WireD)
