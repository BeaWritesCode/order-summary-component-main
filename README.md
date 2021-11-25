# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

I've been a developer for many years but I've not written any HTML or CSS for a (very) long time. Inevitably, building for the web has changed radically - no more floated layouts for a start! I've decided to go back to basics so I'm doing beginners tutorials and this is my first effort.

The provided style guide is a lot more sparse than I'd normally like but I've decided to take that as leeway to interpret some aspects with my own preferences. For example, what does "The designs were created to the following widths" mean, exactly? Why strict px specifications, suggestive of media queries, instead of responsive, flexible growth as the screen dimensions increase? Or is it expected that these are max-width?

Given the supplied background images I decided that the design and style guide require media queries to match the widths of the images so adjusted my CSS accordingly, removing the background image altogether for screen widths greater than the widest of 1440px because it looks silly.

(From the readme template)
Users should be able to:

- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- [The Picalilli CSS Reset](https://piccalil.li/blog/a-modern-css-reset/)

### What I learned

I don't know what CSS needs to be reset any more! I don't even know if it's really necessary these days but a little digging suggests it's still a good idea. Since it's so subjective, could take me hours to investigate and I only need some basics for this exercise I've taken the simple option and used Andy Bell's reset on face value.

I have only needed flexbox to create the designed layout so far. I had a suspicion it would be a combination of grid and flexbox because of the column + row layout within the basket container but an extra block wrapper took care of that. I've finished with the mobile design and am about to embark on adjustments so the page scales per requirements.

### Continued development

Do I really need so many decorative wrappers? I am unhappy with the number I felt were needed in order to layout the design per the spec and can't help but think I've misunderstood or misapplied flexbox. I'll do some more reading - perhaps I don't need flexbox but should have used grid or both, or maybe I've missed some essential property that would streamline my markup.

### Useful resources

- [Mozilla Development Network](https://mdn.dev) - As always, MDN are wonderful and Heaven sent <3

## Author

- Frontend Mentor - [@BeaWritesCode](https://www.frontendmentor.io/profile/BeaWritesCode)
- Twitter - [@BeaWritesCode](https://www.twitter.com/BeaWritesCode)