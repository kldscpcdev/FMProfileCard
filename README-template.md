# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Solution URL](https://codepen.io/kldscpcwebtech/pen/KKNjMqX)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

- Using `<span>` inside `<p>` elements to have them on the same line but with different styles.

```html
<p class="name-stats in-line" id="name">Victor Crest<span style="font-weight: 400; color: hsl(0, 0%, 59%)"> 26</span></p>
    <p class="city">London</p>
```


- using two backround images and positioning them


```css
body {
background-image: url(https://raw.githubusercontent.com/kldscpcdev/FMProfileCard/9fa100a31ee5a1f101b09b4704f96693b2302a2d/bg-pattern-top.svg), url(https://raw.githubusercontent.com/kldscpcdev/FMProfileCard/9fa100a31ee5a1f101b09b4704f96693b2302a2d/bg-pattern-bottom.svg);
  background-size: 1200px;
  background-position: left -300px top -700px, right -300px top 300px;
  background-repeat: no-repeat;
  background-color: hsl(185, 75%, 39%);
}
```


## Author

- Frontend Mentor - [@kldscpcdev](https://www.frontendmentor.io/profile/kldscpcdev)
- Instagram - [@kldscpcdev](https://www.instagram.com/kldscpcdev/)
