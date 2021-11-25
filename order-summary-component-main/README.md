# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: 
- Live Site URL: (https://www.mukeshkenwat.tech)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

To see how you can add code snippets, see below:

```html
<main>
  <section class="section">
        <article class="container-center">
          <div class="summary-container">
            <h1 class="summary__title">Order Summary</h1>
        </article>
      </section>
</main>

```
```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
:root {
  --pale-blue: hsl(225, 100%, 94%);
  --bright-blue: hsl(245, 75%, 52%);
  --very-pale-blue: hsl(225, 100%, 98%);
  --desaturated-blue: hsl(224, 23%, 55%);
  --dark-blue: hsl(223, 47%, 23%);
  }
  .plan__info {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  background-color: var(--pale-blue);
  max-width: 90%;
  margin-top: min(5vh, 1em);
  margin: 1em;
  border-radius: var(--big-radius);
}


```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

css and responsive layouts areas that I want to continue focusing on in future projects. These could be concepts i'm still not completely comfortable with. BEM naming convention techniques I found useful that I want to refine and perfect.

### Useful resources

- [Example resource 1](https://courses.kevinpowell.co/courses/conquering-responsive-layouts) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Website - [Mukesh Kenwat]https://www.mukeshkenwat.tech)
- Frontend Mentor - [@MukeshKenwat](https://www.frontendmentor.io/profile/MukeshKenwat)


## Acknowledgments

David
@Daviddp96(https://www.frontendmentor.io/profile/Daviddp96)

David solution give me some idea to improve my code.....
