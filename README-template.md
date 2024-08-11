# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

While working on this project, I reinforced my understanding of responsive design principles. Implementing both Flexbox and CSS Grid allowed me to gain hands-on experience in creating layouts that adapt seamlessly across different screen sizes.

For example, I used Flexbox for the main layout of the card component and CSS Grid for the internal layout of the card sections. Here's a snippet of the CSS code I was particularly proud of:


css:

.card-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 100%;
}

.card-content {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 1rem;
}


This approach ensured that the card's layout remains consistent and accessible, regardless of the device used to view it.


### Continued development

Moving forward, I plan to further explore advanced CSS Grid techniques and how they can be combined with media queries to create even more dynamic and responsive layouts. Additionally, I want to refine my understanding of CSS custom properties to make my code more maintainable and scalable for larger projects.

## Author

- Frontend Mentor - [@hanifanwary](https://www.frontendmentor.io/profile/@hanifanwary)
- Instagram - [@hanifanwary17](https://www.Instagram.com/@hanifanwary17)



## Acknowledgments

I'd like to thank the Frontend Mentor community for providing such well-structured challenges that continuously push me to improve my skills. The feedback and solutions shared by others have been incredibly helpful in guiding my learning process.