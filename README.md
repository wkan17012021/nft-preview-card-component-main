# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

- This challenge was attempted to keep improving on how quickly I can reproduce the template.
- This project built on the previous one so the turnaround was slightly quicker. Still, a lot of time was spent getting the card to sit in the middle vertically using absolute positioning and altering height property. Adjusting width wasn't as labourous this time round.

### The challenge

- Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover states for interactive elements (main photo, title, author name)

## My process

- Similar to before, use parent container positioned absolute to get the outer card to sit in the middle of the screen and child containers to house the card components.
- Use flex model for the column and inner flex for the two items horizontally.
- Use css pseudo class hover and change the desired elements' color to cyan.

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Wasn't aware of css filter property which was nice to implement.
- Didn't have to use media queries this time: by setting the max-width, the parent card container maintains this thin border with the outer element- in this case the body tag.

### Continued development

- Keep practicing layouts.
- What semantic tags to use.

### Useful resources

- W3

## Author

- wkan17012021

## Acknowledgments

- @AkromDev (Frontend Mentor)
- @Aadv1k (Frontend Mentor)
