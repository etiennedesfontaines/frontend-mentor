# Frontend Mentor - Stats preview card component solution, by Etienne Desfontaines

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

Frontend Mentor challenges are aimed at improving coding skills by challenging it's users to build projects from realistic briefs.

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

## Overview

A challenge to build a card componenet to a client Brief. Solution coded by Etienne Desfontaines, using HTML and CSS.

### The challenge

Build out this card componenet and get it looking as close to the design as possible - use any tools you like.

Follow the supplied style guide. (./style-guide.md)

Users should be able to:

- View the optimal layout depending on their device's screen size.

### Screenshot

![](./screenshots/stats-preview-component-desktop-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/etiennedesfontaines/frontend-mentor/tree/main/newbie/stats-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I chose to follow a Mobile-first workflow.

My initial step was to sketch a quick overview of the project on a piece of paper. It helped me deside how to best structure my HTML to support the CSS that was to follow.

Once the HTML was done, I focused on the mobile styling, working from top to bottom. And then on the desktop styling. When both were done I used my browser dev tools to check a few more devices and orientations, and made any adjustments necessary to ensure responsiveness.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

General:

- It's important to plan a project before initiating the build.
  The plan infroms the HTML structure and semantics, and the HTML structure informs the CSS styling.

  I intially started building without planning. My code, as a restult, very quickly became messy and unecessarily. I deleted it and, after planning my approach, begun again. The outcome was a better solution accomplished using half the amount of code.

- Process documentation is a skill and a useful learning tool.
  It helps to better understand the problem at hand, create practical solutions, and understand the tools you have chosen to solve it with.

CSS:

- Setting an images width to 100% and height to auto maintains the images aspect ratio.

```CSS
img{
  width: 100%;
  height: auto;
}
```

- The CSS Box model.

Git and Github:

- Creating repos, pull requests etc.

- Using the command line to create a powerful workflow between VS Code, Git and Github.

### Continued development

I feel what is most important for my growth as a developer right now, outside of my regular daily studies, is to build as many projects as possible. And to become a more active member of the dev community, by doing code reviews, getting involved in conversations, and blogging.

### Useful resources

- [The CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) - This really helped me fully understand the CSS box model. I highly recomend it to anyone feeling frustrated with their style declarations not giving them the results they intended - There may just be a sneaky collapsing margin in your way...

- [A complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Everything you need to know about Flexbox. Clear and concise!

- [RGB and Hex colors explained](hhttps://www.youtube.com/watch?v=hhI4x6hx21s), [Images, pixels and rgb](hhttps://www.youtube.com/watch?v=15aqFQQVBWU) - The combination of these two videos really helped me better undrstand digital color.

- [A complete guide to submitting your frontend mentor solutions](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) - This guide helped me feel confident that I was following the best practices for this project submission.

## Author

- Frontend Mentor - [@etiennedesfontaines](https://www.frontendmentor.io/profile/etiennedesfontaines)
- GitHub - [etiennedesfontaines](https://github.com/etiennedesfontaines)
- Exercism - [Etienne Desfontaines](https://exercism.io/profiles/etiennedesfontaines)
- Website - [Etienne Desfontaines](#)

## Acknowledgments

To the dev community as a whole - Thank you for all the incredible resources that make self-study possible.
