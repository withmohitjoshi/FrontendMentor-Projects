# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)

### Screenshot

![](./screenshot1.jpeg)
![](./screenshot2.jpeg)

### Links

- Live Site URL: [Single Price Grid Component Master](https://withmohitjoshi.github.io/FrontendMentor-Projects/single-price-grid-component-master/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid

### What I learned

```css
:root {
  /* paddings*/
  --card-padding: clamp(1.2rem, calc(5vw+1.2rem), 2rem);

  /* font sizes*/
  ---fs-card-h1: clamp(1.2rem, calc(2vw + 0.5rem), 1.4rem);
  ---fs-card-1-p: clamp(0.8rem, calc(2vw + 0.2rem), 1rem);
  --fs-card-3-li: clamp(0.7rem, calc(2vw + 0.0125rem), 0.8rem);
}
.card {
  padding: var(--card-padding);
}
.card-1 h1:nth-of-type(1) {
  font-size: var(---fs-card-h1);
}
.card-1 p:last-of-type {
  font-size: var(---fs-card-1-p);
}
.card-3 li {
  font-size: var(--fs-card-3-li);
}
```

### Author

- Frontend Mentor - [@withmohitjoshi](https://www.frontendmentor.io/profile/withmohitjoshi)
