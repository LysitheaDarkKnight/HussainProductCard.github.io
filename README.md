# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS

### What I learned

I've learnt how to center the element whilst using Flexbox using the following codes:

```css
.case{
        position: relative;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
}
```
I was able to make the button size cover the whole content of the menu text by flexing that element:

```css
.menu-text{
            @include set-background($menu-color);
            display: flex;
            flex-direction: column;
            width: 400px;
            height: 600px;
            padding: 40px 45px;
            border-radius: 0 10px 10px 0;

            .btn{
                cursor: pointer;
                display: inline-block;
                @include set-background($cart-color);
                text-align: center;
                padding: 20px;
                border-radius: 10px;
                text-decoration: none;
                font-weight: 700;
                font-size: 19px;
            }
}
```

### Continued development

This was my very first project that I started so I am satisfied with how it turned out. I took this exercise to be able to work on coding on my rather rather than relying on just tutorials. I also used this opportunity to refine my SASS skills since I started this directly after watch SASS Crash course Tutorial from Brad Traversy.

I finished this in approximately 5 work hours over the course of 3 days. Not sure how fast/slow this was, but I would like to be able to finish faster, which is possible by practicing more.

### Useful resources

- [Flexbox Crash Course 2022](https://www.youtube.com/watch?v=3YW65K6LcIA) - Helped me apply Flexbox. Recommend it to anyone wanting to learn Flexbox
- [Full Screen Video Background - HTML & CSS](https://www.youtube.com/watch?v=Gx_7GQtSdpc) - Watching this made me know how to center a content on a page.
- [Sass Crash Course](https://www.youtube.com/watch?v=nu5mdN2JIwM) - Learned SASS from this video.

## Author
- Frontend Mentor - [@LysitheaDarkKnight](https://www.frontendmentor.io/profile/LysitheaDarkKnight)

