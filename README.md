# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![screenshot](./images/Screenshot%202023-02-22%20221701.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

```css
@media (max-width:450px) {
    body {
        background-position:
            top -35rem left -40rem,
            bottom -37rem right -40rem;
    }
}
Use @media to style the svg pictures in the body.

body {
  background-image:
        url(images/bg-pattern-top.svg),
        url(images/bg-pattern-bottom.svg);
    background-position:
        top -520px left -190px,
        bottom -600px right -200px;
    background-size: 900px;
    background-repeat: no-repeat;
}
This sets up the two SVG circles and align them in opposite corners. For background-position, the first line indicates the position for the first svg; second line indicates the 2nd svg's position.
```

### Useful resources

- [CSS Table Alignment](https://www.w3schools.com/css/css_table_align.asp) - This explains how text-align can help center the <td> items to align under the <th> items in the profile stat section.
- [CSS Basics: Using Multiple Backgrounds](https://css-tricks.com/css-basics-using-multiple-backgrounds/) - This is an amazing article which helped me learn how to implement background-iamge in CSS for more than 1 SVG images.
- [background-repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat) - This article explains how to use the background-repeat property to set background images to repeat along the horizontal and vertical axes. I am including this here only because I thought I needed to use this for the background SVG images. It's a good thing to know the difference so I can use it in other situations.

## Acknowledgments

I learned how to make the SVG cirles move to fit the 375px mobile screen from the solution posted by @Hassiai from Frontend Vendor. 
