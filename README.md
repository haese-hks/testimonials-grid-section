# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

For this challenge, I created a responsive testimonial grid layout featuring five testimonial cards. Each card includes an avatar, user name, status, quote, and attribution. The design adapts to different screen sizes using CSS Grid, ensuring an optimal layout on mobile and desktop views. This project emphasizes clean, semantic HTML and well-structured CSS for a smooth and responsive experience.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![MObile Version](<./images/Screenshot (31).png>)

![Desktop Version](<./images/Screenshot (34).png>)

### Links

- Live Site URL: [Github Pages](https://haese-hks.github.io/testimonials-grid-section/)

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/testimonials-grid-section-using-css-grid-B9vzmJuXvu)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla CSS

### What I learned

Through this challenge, I significantly improved my CSS Grid skills, especially in creating a responsive grid layout. I learned how to effectively manage content across multiple screen sizes using Media Queries and how to control the positioning of elements within a grid system. Additionally, I strengthened my understanding of semantic HTML, organizing the content correctly, and ensuring a more maintainable structure. This challenge also helped me get more comfortable with adjusting design elements on different viewports and improving the overall responsiveness of the layout.

To see how you can add code snippets, see below:

```css
@media (min-width: 90em) {
  .container {
    max-width: 90em;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1.5rem;
  }

  .testimonial--daniel {
    grid-column: 1 / 3;
    grid-row: 1;
  }

  .testimonial--jonathan {
    grid-column: 3;
    grid-row: 1;
  }

  .testimonial--jeanette {
    grid-column: 1;
    grid-row: 2;
  }

  .testimonial--patrick {
    grid-column: 2 / 4;
    grid-row: 2;
  }

  .testimonial--kira {
    grid-column: 4;
    grid-row: 1 / 3;
  }
}
```

### Continued development

Next I will improve my responsive layout to be even smoother

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/): The platform I used to learn HTML, CSS, and JavaScript in depth, including lessons on forms, layouts, and responsiveness.

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): My main resource for learning about CSS properties and techniques, especially Flexbox and Media Queries.

- [W3Schools - CSS](https://www.w3schools.com/css/): A handy reference for quick examples and documentation on CSS usage.

- [Frontend Mentor - Blog Preview Card Challenge](https://www.frontendmentor.io/challenges/blog-preview-card-ryaPa2l8M): The main challenge page that provided the design and requirements for this project.

- [Google Fonts](https://fonts.google.com/): I used Google Fonts to find and implement the `Figtree` font for this project.

- [CSS-Tricks - Transform](https://css-tricks.com/almanac/properties/t/transform/): A great resource for understanding how to use the `transform` property, including `scale()` for the hover effect.

- [GitHub Pages Documentation](https://docs.github.com/en/pages): The guide I used to deploy this project on GitHub Pages and make it publicly accessible online.

## Author

- Git Hub: [@haese-hks](https://github.com/haese-hks)
- Frontend Mentor: [@haese-hks](https://www.frontendmentor.io/profile/haese-hks)
- X - [@haese_hks](https://x.com/haese_hks)

## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io) for providing the challenge and design files.
- Big thanks to the [freeCodeCamp](https://www.freecodecamp.org) community for all the learning resources and tutorials.
- Special thanks to [CSS-Tricks](https://css-tricks.com) for their helpful guides and tutorials on CSS.
- Shout out to the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) for being an incredible resource for understanding web technologies.
