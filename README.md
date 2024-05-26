# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Self-Assessment](#self-assessment)
    - [What I learnt](#what-i-learnt)
    - [What I am proud of](#what-i-am-proud-of)
    - [What I would do differently](#what-i-would-do-differently)
    - [Challenges](#challenges)
    - [Help needed](#help-needed)
    - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Final result screenshot](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### Self-assessment

#### What I learnt

I learnt how to import fonts from Google Fonts

First project I made with a mobile-first approach.

#### What I am proud of

nothing in particular.

#### What I would do differently

I woud focus on the layout first and on the styling at the end, instead of doing all at the same time.

#### Challenges

Using `gap` in the text sections created some weird issue whith the media query: While it was perfect with the "mobile diplay", there was a slice shift in the "desktop display".

I needed to use `max-width: calc(100% + 10px);` to compensate the shift.

#### Help needed

n/a

#### Continued development

I want to build more complex layouts with multiple breaking points.
