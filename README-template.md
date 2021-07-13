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

mstach## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [https://github.com/WillianMstach/fem-status-preview-card.io]
- Live Site URL: [https://fem-status-preview-card-io-byj1gf24h-willianmstach.vercel.app/]
## My process
I started by creating the mobile-based layout, using a container and two main divs, then when the document started going to larger widths I needed to use grids. I had a hard time adjusting the image to color using only CSS. And also for the height of the Container div when using 900px resolution. 
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
### What I learned

In this template I learned about changing image colors using only CSS, and a little bit about grid templates.

```css
.image img {
  border-radius: 5px 5px 0 0;
  filter: brightness(0.5) contrast(1) sepia(5) hue-rotate(-125deg) saturate(3);
  width: 90vw;
}
```
```css
  .content  {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 0.1fr;
    grid-template-areas:  "coltext colimg" "coltext colimg" "colstats colimg";
    width: 90vw;
    height: 33vw;
   }
```
### Continued development

I intend to study a little more about grid layouts and alignment adjustment for divs.
### Useful resources
## Author

- Website - [Willian Mstach](https://github.com/WillianMstach)
- Twitter - [@willian_mstach](https://twitter.com/willian_mstach)
## Acknowledgments

