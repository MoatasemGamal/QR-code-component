# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [solution URL here .. repo](https://github.com/MoatasemGamal/QR-code-component.git)
- Live Site URL: [live site URL here](https://moatasemgamal.github.io/QR-code-component/)

## My process

### Built with

- HTML
- CSS custom properties

### What I learned

- center items by position and transform (revision)
- border radius (in parent bigger than child to make a beautiful style)

To see how you can add code snippets, see below:

```html
<div class="qr-code-card">
  <img src="images/image-qr-code.png" alt="" class="qr-code" />
  <h3 class="qr-code-title">
    Improve your front-end skills by building projects
  </h3>
  <p class="qr-code-desc">
    Scan the QR code to visit Frontend Mentor and take your coding skills to the
    next level
  </p>
</div>

<div class="attribution">
  Challenge by
  <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
    >Frontend Mentor</a
  >. Coded by <a href="#">MoatasemGamal</a>.
</div>
```

```css
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap");

.attribution {
  font-size: 11px;
  text-align: center;
  position: absolute;
  bottom: 10px;
  right: 50%;
  transform: translateX(50%);
}

.attribution a {
  color: hsl(228, 45%, 44%);
}

body {
  background-color: #d5e1ef;
  font-size: 15px;
  font-family: "Outfit", sans-serif;
  height: 100vh;
}

.qr-code-card {
  width: 260px;
  box-sizing: border-box;
  padding: 15px;
  background-color: #fff;
  border-radius: 10px;
  text-align: center;
  box-shadow: 1px 1px 10px 7px rgba(0, 0, 0, 0.1);
  /*display center*/
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.qr-code {
  max-width: 100%;
  border-radius: 5px;
}

.qr-code-desc {
  font-size: 13px;
  color: hsl(220, 15%, 55%);
  padding: 0 10px;
}
```

## Author

- Website - [LinkedIn](https://www.linkedin.com/in/moatasem-gamal/)
- Frontend Mentor - [@MoatasemGamal](https://www.frontendmentor.io/profile/MoatasemGamal)
- Twitter - [@MoatasemOff](https://twitter.com/MoatasemOff)
