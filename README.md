# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop preview image for Four card feature section challenge](/images/desktop-preview.png "Desktop preview")
![Mobile preview image for Four card feature section challenge](/images/mobile-preview.png "Mobile preview")

### Links

- Solution URL: [Solution](https://github.com/ag7621/fem-four-card-feature)
- Live Site URL: [Live site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was one of the first projects since starting to learn web development that I was comfortable and happy with the results of creating a responsive site. Having learned a new trick using `clamp`, I decided to try it out on the headings and was pleased with how responsive it was. I did however decide to add in a fallback size in the event it isn't compatible with some web browsers.

I also learned how to use `grid` to create the desktop layout which I was familiar with prior but had not practiced it much. It did pose some challenges with how to properly write the styling for it, but once it was established it made everything else easier to develop.

Overall I had a lot of fun with this one and continue to look forward to new challenges and techniques to learn!

```css
.title {
    color: var(--clr-main-heading);
    font-size: var(--fs-700);
    font-size: clamp(1.50rem, calc(0.84rem + 2.82vw), 2.25rem);
    font-weight: var(--fw-light);
    line-height: 1.3;
}
```

### Continued development

I will continue to learn best methods for creating responsive sites as well as keeping accessibility in mind. BEM and efficient/understandable naming is something I also continue to practice as I complete these challenges. 

### Useful resources

- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.
- [Utopia - Fluid Reponsive Design](https://utopia.fyi/) - A site referred to by Kevin Powell that aided me in creating the responsive type for my headings.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)