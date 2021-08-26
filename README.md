# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<center>

![result-Amelia](./images/result-Amelia.png)

</center>

### Links
- Live Site URL: [Add live site URL here](https://dohoasen.github.io/stats-preview-card-component/)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

I learned how to make responsive designs. Although I made a mistake while making a responsive designs but I was very proud of finishing this challenge. It was really difficult to make all work in the end. I still need to study the css and change some things more, but it was a good way to practice responsive designs!

Some code snippets:

> This is the main code I learned from this challenge!

```html
@media (min-width: 375px) and (max-width: 1024px){
    //things want to upload css
}
```

> I also learned css grid for the first time! It was really hard to understand but I know this is really efficient way to design 

```css
.card-container{
  display: grid;
  grid-template-columns: 55% 45%;
  grid-template-rows: auto;
  grid-template-areas:
  "left-card right-card";
  width: 100%;
  height: auto;
  margin: 15% auto;
  padding-left: 7%;
  padding-bottom: 5%;
  background-color: hsl(244, 38%, 16%);
  border-radius: 5%;
}
```


### Continued development

I need to improve CSS codes and make them shorter and reusable.



## Author

- Website - [Amelia Kang](.)
- Frontend Mentor - [@doHoaSen]
(https://www.frontendmentor.io/profile/doHoaSen)


