# NFT_Preview_Card

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<img width="317" alt="NFT_Card" src="https://user-images.githubusercontent.com/24992697/157094705-53abacad-20eb-4a1c-9cc0-ec78b590f533.png">


## My process

-Firstly I obtained the details of my project like the color schemes of my card and fonts.
-I then gathered dimensions for the different containers in the project.
-Lastly I put it all together with positioning.

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

The project helped reinforce some of the topics that I'm learning regarding position, parent and child relationship in an html document.

To see how you can add code snippets, see below:

```html
<body>
    <div class="card">
      <div class="top-container">
         <img class="img" src="images/image-equilibrium.jpg" alt="">
         <!-- <div class="view">
           <svg class="icon" width="48" height="48" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M0 0h48v48H0z"/><path d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z" fill="#FFF" fill-rule="nonzero"/></g></svg>
         </div> -->
      </div>

      <div class="middle-container" style="margin-left: 20px;margin-bottom: 10px;">
         <h1> Equilibrium #3429</h1>
         <p>Our Equilibrium collection promotes balance and calm.</p>

         <div class="lower-mid">
           <ul>
             <li style = "color: #00FFF7;"><svg class ="eth-logo"width="11" height="18" xmlns="http://www.w3.org/2000/svg"><path d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z" fill="#00FFF8"/></svg> 0.041ETH</li>
             <li class = "days" style = "color: #8BACD9;"><svg width="17" height="17" xmlns="http://www.w3.org/2000/svg"><path d="M8.305 2.007a6.667 6.667 0 1 0 0 13.334 6.667 6.667 0 0 0 0-13.334Zm2.667 7.334H8.305a.667.667 0 0 1-.667-.667V6.007a.667.667 0 0 1 1.334 0v2h2a.667.667 0 0 1 0 1.334Z" fill="#8BACD9"/></svg> 3 days left</li>
           </ul>

         </div>

      </div>

       <hr>

       <div class="bottom-containter">
         <img class="avatar" src="images/image-avatar.png" alt="avatar-img">
         <p class ="footer">Creation of <span>Jules Wyvern</span><p>


       </div>
    </div>

  </body>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```


### Continued development

The following are some topics that I'd like to reinforce.

-Positioning
-Z-indexing
-Margin
-rem



## Author

- Frontend Mentor - [@amath95](https://www.frontendmentor.io/profile/@amath95)
