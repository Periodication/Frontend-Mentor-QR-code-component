# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

- Solution URL: [https://github.com/Periodication/Frontend-Mentor-QR-code-component](https://github.com/Periodication/Frontend-Mentor-QR-code-component)
- Live Site URL: [https://periodication.github.io/Frontend-Mentor-QR-code-component/](https://periodication.github.io/Frontend-Mentor-QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- How to use Figma to help development.
- How to effectively use custom properties.
```css
:root {
  --clr-neutral-100: white;
  --clr-accent-300: hsl(212, 45%, 89%);
  --clr-accent-500: hsl(216, 15%, 48%);
  --clr-accent-900: hsl(218, 44%, 22%);

  --fw-regular: 400;
  --fw-bold: 700;

  --font-family: "Outfit";

  --fs-400: 0.9375rem; /* 15px */
  --fs-600: 1.375rem; /* 22px */

  --lh-100: 1.2;
  --lh-300: 1.4;

  --ls-400: normal;
  --ls-500: 0.2px;
}
```

- Utility classes, why they're important and how to set them up.
```css
.text-neutral-100 {
  color: var(--clr-neutral-100);
}

.text-accent-300 {
  color: var(--clr-accent-300);
}

.text-accent-500 {
  color: var(--clr-accent-500);
}

.text-accent-900 {
  color: var(--clr-accent-900);
}

.bg-neutral-100 {
  background-color: var(--clr-neutral-100);
}

.bg-accent-300 {
  background-color: var(--clr-accent-300);
}

.bg-accent-500 {
  background-color: var(--clr-accent-500);
}

.bg-accent-900 {
  background-color: var(--clr-accent-900);
}

.fw-regular { font-weight: var(--fw-regular); }
.fw-bold { font-weight: var(--fw-bold); }

.heading-text-preset {
  font-size: var(--fs-600);
  line-height: var(--lh-100);
  letter-spacing: var(--ls-400);
}

.body-text-preset {
  font-size: var(--fs-400);
  line-height: var(--lh-300);
  letter-spacing: var(--ls-500);
}
```

### Continued development

I want to focus on how to set up custom properties and utility classes in CSS as I'm still not completely comfortable with using them. I also want to refine my CSS and HTML skills and learn how to write them effectively.

### Useful resources

- Kevin Powell's ["Build a responsive website with HTML & CSS"](https://www.youtube.com/playlist?list=PL4-IK0AVhVjNDRHoXGort7sDWcna8cGPA) series on YouTube is pretty much where I learned all of this. It helped me learned how developers designed websites and understand their thought process. I can't recommend it enough for newbies like me.

## Author

- Frontend Mentor - [@Periodication](https://www.frontendmentor.io/profile/Periodication)

I'm still just a newbie and just started learning front-end a few weeks ago, so if you have some feedback then I would love to hear it!

English isn't my main language and this is the first time I wrote something like this, so I apologize if it sounded weird or if there were some misspellings.
