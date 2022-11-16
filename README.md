# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

## My process

### Built with

- Semantic HTML5 markup
- BEM naming convention
- Sass preprocessor
- Flexbox
- Mobile-first workflow

### What I learned

In this challenge, I have avoided using global CSS reset

```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }
```

Instead, I have used normalize CSS via CDN: *https://cdnjs.com/libraries/normalize*

HTML structure was created using BEM naming convention, which in conjunction with Sass preprocessor made maintaining CSS styles an easy job

For managing available space, I have only used flexbox

Usage of ::before and ::after pseudo-elements for quote tags, in my opinion, is very neat detail
