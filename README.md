# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](/solution-design-screenshots/mobile.jpeg)
![](/solution-design-screenshots/tablet.jpg)
![](/solution-design-screenshots/desktop.jpg)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/responsive-semantic-mobile-first-recipe-page-WXEMzocb0i)
- [Live Site URL](https://freexm1nd.github.io/recipe-page-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This challenge was great semantic HTML practice. I carefully crafted this page to not just reflect the various parts of the recipe, but to also reflect the page's responsive nature.

Below is some code that reflects the things I learned above:

```html
<section class="nutrition">
  <h2>Nutrition</h2>
  <p class="outfit-font outfit-s-150">
    The table below shows nutritional values per serving without the additional
    fillings.
  </p>
  <table class="outfit-font outfit-s-150">
    <tr>
      <td>Calories</td>
      <td class="outfit-600-m">227kcal</td>
    </tr>
    <tr>
      <td>Carbs</td>
      <td class="outfit-600-m">0g</td>
    </tr>
    <tr>
      <td>Protein</td>
      <td class="outfit-600-m">20g</td>
    </tr>
    <tr>
      <td>Fat</td>
      <td class="outfit-600-m">22g</td>
    </tr>
  </table>
</section>
```

```css
.nutrition {
  color: var(--stone-600);
}

.nutrition h2,
td:nth-child(2) {
  color: var(--brown-800);
}

table {
  width: 100%;
  border-collapse: collapse;
}

td {
  padding: 0.75rem 0;
  border-bottom: 1px solid var(--stone-150);
}

td:first-child {
  width: 50%;
  padding-left: 2rem;
  padding-right: 2rem;
}

tr:last-child td {
  border-bottom: none;
}
```

### Continued development

This challenge marks the end of the first Frontend Mentor learning path. I will continue to move through all the learning paths available to me. My number one goal is to complete enough challenges to get a spot in the hiring portal.

### Useful resources

- [Responsively App](https://responsively.app/) - This helped me to test my design by showing me various device resolutions, and allowed me to provide screenshots of my design.

### AI Collaboration

I used Claude during this challenge to help with debugging, brainstorming solutions, and helping to maintain industry best practices.

## Author

- GitHub - [Aaron Robbins](https://github.com/FREExM1ND)
- Frontend Mentor - [@FREExM1ND](https://www.frontendmentor.io/profile/FREExM1ND)

## Acknowledgments

I'm thankful for the team at Responsively for creating a useful development tool.
