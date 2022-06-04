# Stats preview card component solution

![](./screenshots/stats-preview-component-desktop-screenshot.png)

## Table of contents

- [Overview](#overview)
- [Project links](#links)
- [Built with](#built-with)
- [My process](#my-process)
- [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)
- [Author](#etienne-desfontaines)

## Overview

A challenge to build a Stats preview card component.

Use any tools to actualize this [design](./design).

Please be sure to follow the supplied [style guide.](./style-guide.md).

Users should be able to view the optimal layout depending on their device's screen size.

### Links

- [Live site URL](https://stats-preview-card-component-solution-etiennedesfontaines.netlify.app/).

## Built with

- Semantic HTML5
- CSS
  - Flexbox
  - Grid

## My process

### I created a project overview as a sketch on paper.

I find skething a build before executing it helps me approach it with a difinitive plan.
It allows me to consider the project as a whole, considering semantics, styling, funcionality and user experience.
I believe it guides me to deeper learning and a more succesful outcome than I experience if I don't start with a sketch.

#### HTML structure

I considered my HTML from two angles:

- Semantically to increase accessibility and aid search engine optimisation.
- Structurly, to ensure that it makes creating the supplied design as easy as possible.

#### CSS styling

I followed a mobile first approach for my CSS styling.

## What I learned

### General

It's beneficial to plan a project before initiating the build, because a good plan can help infrom the HTML semantics and structure, and make writing CSS a far smoother process.

Process documentation is a valuable skill and a useful learning tool.
I found the practice of documenting my process made me more aware of where I struggled, why I struggled and what I learn't along the way. And it ultimately helped me find my final solution.

### CSS

Image aspect ratio:

Setting an images width to 100% and height to auto maintains the images aspect ratio.

```CSS
img{
width: 100%;
height: auto;
}
```

The CSS Box model:

I learned that all CSS elements are surrounded by a box which affects how they behave.

Understanding the different CSS box models (standard and alternate), along with their anatomy (margin, border, padding, content), and how they behave differently relative to which box box type (block, inline, inline-block, flex and grid) is applied, made my CSS styling far more predictable.

### Git and Github

I learned to create repositories, push edits and pull and commit requests.

### Bash and the CLI

I learned the basics of Bash and how to navigate my local drives and file structures using the command line.

And how to utalise the command line with github.

## Acknowledgments

The dev community as a whole, for all the incredible documentation and information that makes learning frontend development possible.

## Etienne Desfontaines

- Frontend Mentor - [@etiennedesfontaines](https://www.frontendmentor.io/profile/etiennedesfontaines)

- Exercism - [Etienne Desfontaines](https://exercism.io/profiles/etiennedesfontaines)
