# Frontend Mentor - Stats preview card component solution

This is my solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./Screenshot_desktop)
![](./Screenshot_mobile)

## My process

### Built with

- Semantic HTML5 markup
- CSS Styling
- Flexbox
- Bootstrap - made responsive part a lot easier!

```css

LOT OF MEDIA QUERIES TO MAKE THIS THING RESPONSIVE!

/* Media Queries */

@media (max-width: 375px) {
  .main-container {
    flex-direction: column-reverse;
    height: 100vh;
    width: 80%;
    margin: 20px auto;
  }

  .image {
    background: url("../images/image-header-mobile.jpg") no-repeat center
    center/cover;
    width: 100%;
    height: 30%;
    border-top-left-radius: 10px;
    border-bottom-right-radius: 0;
  }

  .image::after {
    border-top-left-radius: 10px;
    border-bottom-right-radius: 0;
  }

  .content {
    width: 100%;
    height: 70%;
    text-align: center;
  }

  .container {
    max-width: 100%;
    max-height: 100%;
    margin: 30px auto;
  }

  .container h1 {
    max-width: 100%;
    font-size: 28px;
    margin-bottom: 20px;
  }

  .container p {
    font-size: 16px;
    margin-bottom: 35px;
  }

  .container .stats {
    flex-direction: column;
  }

  .container .stats .companies h4,
  .container .stats .templates h4,
  .container .stats .queries h4 {
    font-size: 16px;
    margin-bottom: 2px;
  }

  .container .stats .companies span,
  .container .stats .templates span,
  .container .stats .queries span {
    display: block;
    font-size: 10px;
    margin-bottom: 30px;
  }
}

@media (min-width: 376px) and (max-width: 768px) {
  .main-container {
    flex-direction: column-reverse;
    height: 100vh;
    width: 80%;
    margin: 20px auto;
  }

  .image {
    background: url("../images/image-header-mobile.jpg") no-repeat center
    center/cover;
    width: 100%;
    height: 30%;
    border-top-left-radius: 10px;
    border-bottom-right-radius: 0;
  }

  .image::after {
    border-top-left-radius: 10px;
    border-bottom-right-radius: 0;
  }

  .content {
    width: 100%;
    height: 70%;
    text-align: center;
  }

  .container {
    max-width: 100%;
    max-height: 100%;
    margin: 30px auto;
  }

  .container h1 {
    max-width: 100%;
    font-size: 35px;
    margin-bottom: 20px;
  }

  .container p {
    font-size: 16px;
    margin-bottom: 35px;
  }

  .container .stats {
    flex-direction: column;
  }

  .container .stats .companies h4,
  .container .stats .templates h4,
  .container .stats .queries h4 {
    font-size: 30px;
    margin-bottom: 2px;
  }

  .container .stats .companies span,
  .container .stats .templates span,
  .container .stats .queries span {
    display: block;
    font-size: 16px;
    margin-bottom: 30px;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .container {
    width: 80%;
    margin-top: 30px;
    margin-left: 30px;
  }

  .container h1 {
    font-size: 30px;
  }

  .container p {
    margin-bottom: 40px;
  }

  .container .stats .companies,
  .container .stats .templates,
  .container .stats .queries {
    margin-right: 20px;
  }
}

@media (min-width: 1025px) and (max-width: 1200px) {
  .container {
    width: 80%;
    margin-top: 50px;
    margin-left: 40px;
  }

  .container p {
    margin-bottom: 50px;
  }

  .container .stats .companies,
  .container .stats .templates,
  .container .stats .queries {
    margin-right: 30px;
  }
}

@media (min-width: 1201px) and (max-width: 1399px) {
  .container {
    width: 80%;
  }

  .container p {
    margin-bottom: 60px;
  }

  .container .stats .companies,
  .container .stats .templates,
  .container .stats .queries {
    margin-right: 30px;
  }
}

@media (min-width: 1400px) {
  .container {
    width: 70%;
  }

  .container p {
    margin-bottom: 60px;
  }

  .container .stats .companies,
  .container .stats .templates,
  .container .stats .queries {
    margin-right: 40px;
  }
}

```

## Author

- Frontend Mentor - [@MladenAntic](https://www.frontendmentor.io/profile/MladenAntic)

