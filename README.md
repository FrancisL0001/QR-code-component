# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

This project was about designing a basic QR code component used to access the Frontend Mentor(https://www.frontendmentor.io) website using basic HTML5 and CSS3 for build up and styling. 

### Screenshot

![Screenshot sample](screenshot.png)

### Links

- Live Site URL: (https://qr-code-component-2vgo-git-main-francisl0001s-projects.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive website design

### What I learned

While working on this project, I developped my basic html and CSS skills. I developped the basic html structure mainly following the guidelines provided and then went forward to create a CSS file to style the website. 

I also learnt how to make my website design responsive using "@media" and how to position different elements relative to each other using both flex and block designs. 

I also used this oportunity to get better with the git syntax and test Vercel to host my website(visit the link above). 

Nonetheless, I had a lot of difficulties with centralizing the QR code's box vertically and ended up going for introducing a padding above the box as follows:

```css
.background{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 90%;
    padding-top: 6%;
}
```

I hope to eventually find a better way to position this type of components relative to any direction soon.

Overall, this proved just as challenging as it was interesting.


### Continued development

I intend to continue working on the responsiveness of the website and perhaps build it to tackle different languages aside from english. 


## Author

- Frontend Mentor - [FrancisL001](https://www.frontendmentor.io/profile/FrancisL0001)
- GitHub - [FrancisL0001](https://github.com/FrancisL0001)

## Acknowledgments

I got a lot of help from [Josias](https://github.com/JosiasAurel) during the designing phases, especially relative positioning of items, pushing to GitHub and hosting on [vercel](https://vercel.com/). 
