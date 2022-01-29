# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
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

- Build a testimonial grid section
- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

This project served as an introduction to CSS Grid. It taught me how to lay a page out using a combination of CSS Grid and Flexbox. I also realized I still have a lot to learn when it comes to CSS Grid.  

```css
main {
        width: 75%;
        grid-template: 1fr 1fr / 1fr 1fr 1fr 1fr;
    }

    .daniel {
        grid-column: 1 / 3;
        background-position: top right 60px;
    }

    .jonathan {
        grid-column: 3 / 4;
    }
```

### Continued development

I wanna learn more about CSS Grid and progress into using gradients and animations in CSS, perhaps adding Bootstrap down the line.

### Useful resources

- [CSS Tricks](https://css-tricks.com/guides/) - This helped me use CSS Grid, as I had to refer to this guide several times in the process of making this project.

## Author

- Website - [Mikhael Opeyemi-Olatunji](https://www.your-site.com)
- Frontend Mentor - [@mikhael-oo](https://www.frontendmentor.io/profile/mikhael-oo)
- Twitter - [@tha_mikky](https://www.twitter.com/tha_mikky)
