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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screen.PNG)

### Links

- Solution URL: [Solution URL](https://github.com/pnrmmt/rontendmentor-newbie6)
- Live Site URL: [Live site URL](https://pnrmmt.github.io/rontendmentor-newbie6/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
I learned the grid structure and learned how to move content on responsive screens.


```css
@media only screen and (max-width:425px){
   body{
    text-align: center;
    padding: 30px;
   }
   .container{
    grid-template-columns: 1fr;
    
   }
   .get{
    padding:12% 8%;
   }

   .purple{
    order: -1;
   }
```


## Author

- Frontend Mentor - [@pnrmmt](https://www.frontendmentor.io/profile/pnrmmt)



