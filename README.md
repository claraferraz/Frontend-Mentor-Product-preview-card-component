# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](Assets/My%20solution/solution-desktop-selected.png)
![](Assets/My%20solution/solution-desktop.jpg)
![](Assets/My%20solution/solution-mobile.png)

- On the solution-desktop-selected file there's no cursor because of the print screen, but if you want to check it out feel free to click on the solution page below :)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- [Figma](https://www.figma.com/downloads/) - for styles


### What I learned

- On this project I could practice what I've been learning on an Udemy HTML and CSS course. The things that I've practiced the most were flexbox and media query on CSS. The HTML part was pretty simple and straight forward, I've used mostly divs to organize the blocks.
- Before this challenge I had never used Figma, and I really liked it because it helps out a lot to check the specific configurations to use in the CSS, for example, the exact colors, fonts and even the distance between each block, which for that I used margins and paddings to set them up right.

Here are some examples:

For the block organizing I used mostly divs:

```html
  <div id="background">
    <div class="product">
      <div>
        <p id="product-img">
      </div>
      <div id="product-txt">
        ...
      <div> 
      <button>...</button>
```
To organize my blocks in the center I used flexbox:
```css
#background {
    display: flex;
    background: #F2EAE2;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.product {
    display:flex;
    width: 600px;
    height: 450px;
    align-items: stretch;
    border-radius: 10px;
    overflow: hidden;
    justify-content: center;
```
Since I did a desktop-first workflow, I added a media query for the mobile CSS:

```css
@media (max-width: 376px){...}
```
I also learned how to put a background image on CSS:
```css
#product-img{
        background-image: url("Assets/images/image-product-mobile.jpg");
        background-size:cover;
        height: 240px;
        width: 343px;
}
```
And I'm pretty proud of my button because on the design the text was slightly higher than the cart icon and I managed to do it the same way on my solution by adding IDs to the icon and the text:

```css
#button-txt{
    font-family: Montserrat;
    font-size: 14px;
    font-weight: 700;
    line-height: 17px;
}
#button-icon{
    margin-right: 11.61px;
    height:16px;
    width:14.39px;
}
```
### Continued development

This is my first challenge with Frontend Mentor and it gave me the perspective on how it is to code someone else's design. I intend to continue doing other challenges and learning even more. I also intend to start doing some challenges with Javascript once I study some more.


### Useful resources

- [mdn web docs](https://developer.mozilla.org/) - This helped me remind myself of some properties that I didn't remember or hadn't practiced enough
- [css-tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is an amazing article which helped me finally understand the difference between align-items and justify-content. A senior dev showed this to me and he sais he still uses it to this day.


## Author

- Website - [Clara Ferraz](https://claraferraz.github.io/)
- Frontend Mentor - [@claraferraz](https://www.frontendmentor.io/profile/claraferraz)

## Acknowledgments

Thank you André Castelo for supporting me in this journey to learn web development, I couldn't do it without your support. And thank you for showing me the css tricks website and the Frontend Mentor.
