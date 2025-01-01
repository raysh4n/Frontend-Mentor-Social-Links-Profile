# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)




### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot
Desktop:
![](./Screenshot%202024-12-31%20at%2020-58-24%20Frontend%20Mentor%20Social%20links%20profile.png)

Mobile: 
![](./Screenshot%202024-12-31%20at%2020-59-47%20Frontend%20Mentor%20Social%20links%20profile.png)

### Links

- Solution URL: [click here](https://www.frontendmentor.io/solutions/social-links-profile-with-little-animations-0WwPfoTYBx)
- Live Site URL: [click here](https://social-links-profile-raysh4n.netlify.app/)

## My process
Created a container which has card div and attribution div. The container is set to grid and `place-items:center` to the child elements to be horizontally and vertically centered. The attribution is being kept to the bottom by using `grid-template-rows: 1fr auto;` at the container. 

### Built with

- Semantic HTML5 markup
- BEM
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Animations and transitions

### What I learned

- `box-sizing: border-box;` works only when the element size is specified in a fixed size via width/height. That's why padding code below can increase the height and width of the card since no fixed size mentioned for the width/height. 
- From ChatGPT: 
box-sizing: border-box; ensures the padding and border are included within the defined width and height, but if you don't set a fixed width or height, the padding will still cause the card to expand beyond what you might expect. You can control this behavior by either specifying a fixed size for the .card or adjusting the layout to account for the padding.

```css
.card {
    display: grid;
    place-items: center; 
    padding: 2rem 3rem;  /*this one*/
```

<br/><br/><br/>

 - `text-align:center` will allow the child elements which are inline, inline block, or inline-table elements to be centered. However, won't affect block elements (block element doesn't respond to text-align).
- Normally, good practice is to use code like below, but in this case, no need to use it. 

```css
 img,
picture,
video,
canvas,
svg {
    display:block;
    user-select: none;
    max-width: 100%;
} 
```






