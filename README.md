# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Solution on FrontendMentor](https://www.frontendmentor.io/solutions/grid-section-s0VVXmFk0)
- Live Site URL: [Github Pages Link](https://landon345.github.io/frontendmentor-testimonial-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to work with css grid better. I also learned how to select deep into the DOM with css.

```html
<div class="card gray">
  <div class="img-and-profile">
    <img
      src="./images/image-jonathan.jpg"
      alt="Johnathan"
      class="profile-image"
    />
    <div class="profile">
      <p class="name">Jonathan Walters</p>
      <p class="verified">Verified Graduate</p>
    </div>
  </div>
  <p class="top-para">The team was very supportive and kept me motivated</p>
  <p class="bottom-para">
    “ I started as a total newbie with virtually no coding skills. I now work as
    a mobile engineer for a big company. This was one of the best investments
    I’ve made in myself. ”
  </p>
</div>
```

```css
.name {
  font-weight: 800;
  font-size: 18px;
  margin-bottom: 5px;
}
.verified {
  font-size: 15px;
  color: hsl(210, 2%, 80%);
}

.white > .img-and-profile > .profile > .name {
  color: hsl(219, 29%, 14%);
}

.white > .img-and-profile > .profile > .verified {
  color: hsl(0, 0%, 50%);
}
```

### Continued development

I'll focus on doing cool stuff with css grid.

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

This project took me about 1.5 hours in total.
