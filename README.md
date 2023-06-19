# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size. TThere are desktop and mobile layouts.
- See hover states for interactive elements. There are three buttons each with a hover state.

### Screenshots

![Desktop screenshot](images/screenshot-desktop.png)
![Mobile screenshot](images/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/harnettd/3-column-preview-card](https://github.com/harnettd/3-column-preview-card)
- Live Site URL: [https://harnettd.github.io/3-column-preview-card/](https://harnettd.github.io/3-column-preview-card/)

## My process

### Built with

- HTML5
- CSS with Flexbox and BEM methodology
- Sass

### What I learned

I completed this project mainly to practice techniques I've learned from previous projects. Also, I took the opportunity to implement some tips and tricks that I picked up from Frontend Mentor feedback as well as to implement a few simple upgrades. Namely,

- I used the CSS trick `html {font-size: 62.5%}` to set `10rem` to `16px`. (Actually, in my code, I used the wrong percentage, but going back and recalculating all lengths seems like a lot of unnecessary work. I'll fix the typo in future projects.)
- I set the card's width using `max-width: 100vw` and the card's height using `min-height: 100vh`. This is the first time I've used `vw` and `vh` units.
- I minified my CSS (even though it's hardly necessary for a project of this size).
- To build the project, I used Make (although Grunt and Gulp are better suited to the task).

### Continued development

- I plan to learn Grunt and Gulp to automate build processes on future projects.

### Useful resources

- [How to Minify CSS and Speed Up Your Website](https://blog.hubspot.com/website/minify-css) - I learned different ways to minify CSS from this webpage. I went with css-minify.
- [Learn Makefiles With the tastiest examples](https://makefiletutorial.com/) - I hadn't written a Makefile for a while. This website served as a great refresher.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.
