# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)




### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot
Desktop:
![](./Screenshot%202024-12-31%20at%2020-58-24%20Frontend%20Mentor%20Social%20links%20profile.png)

Mobile: 
![](./Screenshot%202024-12-31%20at%2020-59-47%20Frontend%20Mentor%20Social%20links%20profile.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/social-links-profile-with-little-animations-0WwPfoTYBx)
- Live Site URL: [Add live site URL here](https://social-links-profile-raysh4n.netlify.app/)

## My process


### Built with

- Semantic HTML5 markup
- BEM
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Animations and transitions

### What I learned


- `box-sizing: border-box;` works only when the element size is specified in a fixed size via width/height. That's why padding code below can increase the height and width of the card since no fixed size mentioned for the width/height. 


From ChatGPT: 
box-sizing: border-box; ensures the padding and border are included within the defined width and height, ==but if you don't set a fixed width or height, the padding will still cause the card to expand beyond what you might expect.== You can control this behavior by either specifying a fixed size for the .card or adjusting the layout to account for the padding.


```css
.card {
    display: grid;
    place-items: center; 
    padding: 2rem 3rem;  /*this one*/
```


### Continued development
Currently there is no media queries implemented.  
Perhaps make the card bigger for desktop version. 





