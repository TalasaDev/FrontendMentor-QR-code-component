# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](./screenshot-QR-code-component.png)


### Links

- Solution URL: (https://github.com/TalasaDev/FrontendMentor-QR-code-component/settings/pages)](https://your-solution-url.com)
- Live Site URL: (https://your-live-site-url.com](https://talasadev.github.io/FrontendMentor-QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- To create VARIABLES to reuse them during my coding making it more efficient.
```css
:root {
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --grayish-blue: hsl(216, 15%, 48%);
    --blue: hsl(218, 44%, 22%);
}
```
- **Centering a DIV:**: Repeat avec moi: margin: auto, margin: auto, margin: auto,margin: auto, margin: auto, margin: auto,margin: auto, margin: auto, margin: auto,margin: auto, margin: auto, margin: auto,margin: auto, margin: auto, margin: auto,margin: auto, margin: auto, margin: auto,...
  Centering a <div>, in this case, the Qr component. I started with "mobile-first design" where everything was marvelously perfect in a to-good-to-be-truth scenario. When changing the size of the browser, everything stayed stuck to the left side. It was super mean. Adding in the body {margin: auto} is the ticket to Wonderland.

```HTML
body {    
    margin: auto;    
}
```
- **Object-fit property:** sets how an image or video is resized to fit its container. It can take values like fill, contain, cover, none, and scale-down, allowing you to maintain aspect ratios or fill the space as needed.



### Continued development

In the next projects, I will focus in working with different layouts, not only flexbox,responsiveness, and using the proper mark up to warranty a good accessibility.

### Useful resources

- w3schools
- MDNdocs
- stackoverlow
- css tricks

## Author

- Website - [(https://www.coming-soon.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/TalasaDev)
- Twitter - [@really-coming-soon](https://www.twitter.com/yourusername)






