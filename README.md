# QR Code Component

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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1. Start with creating the HTML File
2. Build the CSS File
3. Add the background colors, font-size
4. Work on the screen sizing

### Built with3
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

For screen sizing, it is ideal to start with a mobile size.
Use of flex as display within the body and media query for the min-width and max-width

To see how you can add code snippets, see below:


```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    max-height: 100vh;
}

@media (min-width: 480px) and (max-width: 1200px) {
    .card {
      max-width: 400px;
    }
  
    h1 {
      font-size: 1.75rem;
    }
  
    .card-text {
      font-size: 1.125rem;
    }
  }
  
```

### Continued development

Become more comfortable with screen sizing using Flexbox, CSS Grid and Media Query. 


## Author

- Frontend Mentor - [@DarkMoonLit](https://www.frontendmentor.io/profile/DarkMoonLit)

