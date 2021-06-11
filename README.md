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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is a challenge provided by frontendmaster.io and involves creating a website and designing it with HTML5 and CSS based on the instructions given to us.

This is the first challenge under "newbie".

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://rrgmon.dev/frontendmentor-challenge-newbie-1/)
- Live Site URL: [Add live site URL here](https://rrgmon.dev/frontendmentor-challenge-newbie-1/)

### Built with

- Semantic HTML5 markup
- SASS
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt how to arrange sections of a page for each viewport size. It was pretty hard at first and took a while to get the site to look like the reference image. Hopefully I can improve my time, and speed!

I experimented with flexbox, especially with the media queries section.

```scss
@media (min-width: 700px) {
  .container {
    display: flex;
    flex-direction: row-reverse;
    justify-content: center;
    align-items: center;

    height: 36rem;
    width: 100rem;
    overflow: hidden;

    img {
      max-width: 50%;
    }
    .text--div {
      text-align: left;
      margin: 0 5rem;
    }
    .stats--div {
      flex-direction: row;
      text-align: left;
      margin: 0 5rem 0 0;
      h3 {
        font-size: 2rem;
      }
    }
  }
}
```

### Continued development

I definetly need to work on how to figure out the heights and widths for the content. Since that is where I had a lot of trouble! I should also improve on my "cleanliness" of my code. It is bit here and there, and I repeated myself a lot.

## Author

- Website - [Rohit Regimon](https://rrgmon.dev)
- Frontend Mentor - [@rrgmon](https://www.frontendmentor.io/profile/rrgmon)

## Acknowledgments

Does google and stackoverflow count?
