# Social links profile

# Frontend Mentor - Social links profile

This is a solution to the [Social links profile](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

-PC screenshot :
![](./destkop-design.png)


-Phone screenshot:

![](./mobile-design.png)

-Active States:

<img src="https://raw.githubusercontent.com/shariar-ahamed/Social_links_profile/main/active-states.jpg" alt="Active States" width="466" height="953">

### Links

- Solution URL: (https://shariar-ahamed.github.io/Social_links_profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Use Some Tag


### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used.
Always open to any comments  

```css
/* Card Styles */
.card {
    background-color: var(--greyB);
    width: 350px;
    padding: 20px;
    border-radius: 12px;
    text-align: center;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
}

/* Profile Image */
.card img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 15px;
}

/* Name & Location */
.card h2 {
    color: var(--white);
    font-size: 20px;
    font-weight: 700;
}

.card h4 {
    color: var(--green);
    font-size: 14px;
    font-weight: 600;
    margin: 5px 0;
}

/* Description */
.card p {
    color: var(--white);
    font-size: 14px;
    margin: 15px 0;
}

/* Social Links */
.social-links {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-top: 15px;
}
```

### Continued development
*****************

## Author
- Frontend Mentor - [@sharierahmed11](https://www.frontendmentor.io/profile/sharierahmed11)
