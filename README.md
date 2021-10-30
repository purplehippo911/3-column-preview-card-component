# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Desktop-design:
![Screenshot (22)](https://user-images.githubusercontent.com/76628594/139417014-91f54ed9-09f0-4174-8bc8-d0510d67b02c.png)

Mobile-design:
![my_version 2](https://user-images.githubusercontent.com/76628594/139416816-9a938da0-978f-48a4-ba1c-7d153d74a885.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-landing-page-using-grid-OeraGxOSe)

- Live Site URL: (https://purplehippo911.github.io/3-column-preview-card-component/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- CSS Grid

### What I learned

I learned a bit about pseudo-element and classes, and how to use them, but the most important thing I learned was where I stood when it came to my understanding of frontend development.

Some code I wrote:

```Html
 <div class="box">
        <section class="last_coloumn">
          <img
            class="card_logo"
            src="icons/icon-luxury.svg"
            alt="luxury icon"
          />
          <h1 class="heading">LUXURY</h1>
          <p class="card_info">
            Cruise in the best car brands<br />
            without the bloated prices.<br />
            Enjoy the enhanced comfort<br />of a luxury rental and arrive<br />
            in style.
          </p>
          <button class="button--last_coloumn">Learn More</button>
        </section>
      </div>
```

```Css
.container {
  width: clamp(375px, 84%, 1440px);
  height: auto;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  padding: 3.2rem 3rem;
  box-sizing: border-box;
}
```

### Continued development

I think I should learn more about psuedo elements and classes, and probably start learning JS bit by bit, and learn some Css frameworks. I should also try to get more comfortable with using git, and learning more about flex and grid, so I can get better at aligning things.

### Useful resources

-Fireship(https://www.youtube.com/watch?v=Qhaz36TZG5Y&ab_channel=Fireship) This channel helped me understand Css much easier and I learned that I could clamp the content instead of making meadia queries. I really his style of explaining things and that he is using gifs in his videos that make it more understandable(and sometimes funny).

- Ihatetomatoes(https://www.youtube.com/watch?v=xNVM5UxlFSA&ab_channel=Ihatetomatoes) - This is another amazing channel which helped me, when I ran into a problem with merging my branch to the main branch. I'd recommend it to anyone who thinks git is too complicated to learn.

-OnlineTutorial(https://www.youtube.com/watch?v=oxi7pfa5DKA&t=12s&ab_channel=OnlineTutorials)- This channel helped me when I was trying to make responsive boxes. It has tutorials on Html and Css.

## Author

- Frontend Mentor - [@foxynoxy](https://www.frontendmentor.io/profile/purplehippo911)

## Acknowledgments

I got some inspiration from @somebodysson777's solution. You should go and check out his solution:(https://github.com/somebodysson777/3-coloumn-preview-card).
