# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](./screenshot.jpg)
![](./mobile-preview.jpg)


### Links

- Solution URL: (https://github.com/DMKALALA/Front_end_mentor_html_css)
- Live Site URL: (https://dmkalala.github.io/Front_end_mentor_html_css/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used.
Always open to any comments


```css
body{
    
    font-family: 'Outfit', sans-serif;
    background-color: rgba(148, 189, 194, 0.397);
    font-size: 11px;
    color: hsl(0, 0%, 0%);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 8px;
    text-align: center;
    height: 100vh; /* we needed to include height:100vh to make it full  another way you do it is by making body,html{ height:100%;}*/
    /*
    100VH would represent 100% of the viewport's height, or the full height of the screen. 
    And of course, VW stands for “viewport width”, which is the viewable screen's width. 
    100VW would represent 100% of the viewport's width, or the full width of the screen.*/
}

.content{
    background-color: white;
    max-width: 250px;
    padding: 10px;
    border: white solid 3px;
    border-radius: 10px;
    margin-bottom: 10px;
    
}


```

### Continued development

I would like to make my own QR Generator so this could be used as a default template.

The qr code could be links to a document or something along those ways. Going to think about something useful that could come in handy.

### Useful resources

- [FLEXBOX FROGGY](https://flexboxfroggy.com/#es) - This helped me to understand better how to use flexbox.


## Author

- Frontend Mentor - [@DMKALALA](https://www.frontendmentor.io/profile/DMKALALA)

## Acknowledgments


At some point i was a little stuck with setting the style for the image. And i found this video helpful.

(https://www.youtube.com/watch?v=JFyMWwOxHYM&t=865s)
