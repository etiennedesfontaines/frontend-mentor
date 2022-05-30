# 3-column preview card component - Frontend Mentor

![](./screenshots/3-column-preview-card-component-desktop-screenshot.png)

## Intro

Hey there! :wave:

Thanks for checking out my solution to Frontend Mentor's [3-column preview card component challenge](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

Please feel free to share your feedback and let me know how I might improve this iteration.

## Overview

For this challenge, I used...

- Semantic HTML5 markup
- Sass
- Flexbox

## What I learnt

Sass basics:

- Partials
A partial is a Sass file named with a leading underscore. e.g
\_global.scss
\_desktop.scss
\_mobile.scss

```scss
@import "global";
@import "desktop";
@import "mobile";
```

- Variables

```scss
$variable-name: hsl(31, 77%, 52%);
```

- Mixins
Mixins allows the grouping of css variables that you want to reuse throught your site.

A mixin is declared as follows:

```scss
@mixin flex($direction, $justify, $align, $wrap) {
	display: flex;
	flex-direction: $direction;
	justify-content: $justify;
	align-items: $align;
	flex-wrap: $wrap;
}
```

A mixin is called as follows:

```scss
@include flex(column, center, stretch, wrap);
```

- Nesting

```scss
.suv {
	background: $suv-cyan;
	border: 0.2rem solid $suv-cyan;

	button {
		color: $suv-cyan;
		border: 0.2rem solid $suv-cyan;

		&:hover {
			border: 0.2rem solid $light-gray;
			background: transparent;
			color: $light-gray;
		}
	}
}
```

## Solution

- [Live site URL](https://3-column-preview-card-component-solution-etiennedesfontaines.netlify.app/)

- [My solution on Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-3column-preview-card-component-using-sass-RbzOWpSuF)
