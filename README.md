# Frontend Mentor - Product preview card component solution

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (one for mobile view and another for desktop view)
- See hover and focus states for interactive elements

### Screenshot

Desktop View
![Desktop view for the Product preview card component coding challenge](./design/desktop-view.png?raw=true)

Mobile View using Iphone XR

![Mobile view for the Product preview card component coding challenge](./design/mobile-view.png?raw=true)

Active State
![Active states for the Product preview card component coding challenge](./design/active-state.png?raw=true)

### Links

- Live Site URL: [Github Pages link](https://blackpinkrose.github.io/product-preview-page/)

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- CSS Grid

### What I learned

This is my first practice project where I wasn't just following an instructor on an online tutorial and is actually my second attempt in building this project. I've found that I encountered issues on placing repeating codes or repeating CSS selectors and even using CSS styles that I'm not entirely sure what is doing which made my first attempt miserable.

I tried attempting everything again from scratch and learned that I shouldn't skip the planning phase and find similar portions of the page that I can group together to apply the same styles. This somewhat made my project more maintainable(I guess) and workable atleast that allowed me to finish what was required on the challenge.

I did use mobile-first approach in developing and used CSS grid to create my two-column layout for the desktop view. However, I didn't plan on using grid on my mobile view which is why I just placed it for my desktop view. I'm not entirely sure if this approach is correct or not, since I can just use CSS Grids for my mobile view as well.

```css
@media screen and (min-width: 790px) {
  section {
    display: grid;
    grid-template-columns: repeat(2, 300px);
    height: 450px;
    margin: 20vh calc(50% - 300px) 3em;
  }
}
```

### Continued development

From this point onwards, I'm planning to see how others attempted this challenge (even though this is a newbie project and I should practice other projects) and take lessons on them how they designed theirs. I like to see how they planned things out and what approach they used that I might help me in the future too.

If given the time and interest, I might update this site once I learned other approaches and techniques and hopefully make this site more maintanable and workable.

### Useful resources

- Google and StackOverflow
  I just google things out and it leads me to some stackoverflow link which I often find useful in many scenarios.

- W3Schools
  When I'm unsure about some syntax, or how a css style works out, I sometimes go here.

- Youtube
  When I want to dive a little bit deeper on a topic or an approach, I usually go here.

- Team TreeHouse
  I'm currently taking their Front-End Web Development track here and where most of my foundation in web development was built.

## Author

- Website - Soon
- Frontend Mentor - [@blackpinkrose](https://www.frontendmentor.io/profile/blackpinkrose)
