# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](screenshot.jpg)


### Links

- Solution URL: [https://github.com/Bebe-dev/nft-review-card-component-main]
- Live Site URL: [https://bebe-dev.github.io/nft-review-card-component-main]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.
I learnt to how to add overlay to an image properly on hover.


```html
  <div class="image">
      <img id="main" src="images/image-equilibrium.jpg" alt="equilibrium">
      <div class="overlay"></div>
  </div>

```
```css
.image{
  position: relative;
  width: 100%;
  
}
.overlay{
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  transition: 0.5s ease;
  opacity: 0;
  background-color: hsl(178, 100%, 50%);
  border-radius: 10px;
}
.image:hover .overlay{
  opacity: 0.5;
}

```

### Continued development

I intend to practice more on overlay using css and the different types of transition that can used.

### Useful resources

- [Example resource 1](https://www.w3docs.com) - This helped me with overlay over images using css. It was explanatory and clear.

## Author

- Frontend Mentor - [@Praise](https://www.frontendmentor.io/profile/Praise)
- Twitter - [@fisayo2_5](https://www.twitter.com/fisayo2_5)
- GitHub - 
[@Bebe-dev](https://github.com/Bebe-dev)

