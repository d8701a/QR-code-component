# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


### Screenshot

(images/screenshot_solution.jpg)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- logical CSS function max()


### What I learned

Trying to use logical CSS functions such as min() and max() is still more of a guessing game. I decided to go with min() for setting width to achieve responsiveness but it took me a couple of tries and changing values
to achieve the wanted width on all screens. 

Now my card is responsive, it will never get smaller than 290px and it's even adjusted to iphone5 small screens (320px).

To achieve this, I added this line:

.card_wrapper {
  width: max(10%, 290px);
}

### Continued development

In future I'd like to spend more time working on creating a layered card or adding more interactivity using JS. 
Also I'd like to work more on responsiveness achieved by using min(), max() and clamp() functions.






