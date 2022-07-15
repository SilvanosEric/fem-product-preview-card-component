# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
    - [Mobile](#mobile)
    - [Desktop](#desktop)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Bundled with](#bundled-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Mobile

![Screenshot of the mobile version of the website](./mobile.png)

#### Desktop

![Screenshot of the desktop version of the website](./desktop.png)

### Links

- Solution URL: [Source code](https://github.com/SilvanosEric/fem-product-preview-card-component)
- Live Site URL: [Live site](https://silvanoseric.github.io/fem-product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [CUBE CSS](https://cube.fyi/)
- [BEM CSS](http://getbem.com/)

### Bundled with

- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling

### What I learned

- [Change base dir for vite](https://stackoverflow.com/questions/69744253/vite-build-always-using-static-paths) - By default the base dir in vite is set to "/". Due to the hosting environment (GitHub Pages), root hosting is resticted to only one repo (the portfolio repo). Other repos are hosted one level down the root. This caused links set with their base dir to "/", to break.

- [Host dist and src folder in on repo without overlap](https://sangsoonam.github.io/2019/02/08/using-git-worktree-to-deploy-github-pages.html)

### Continued development

- CUBE CSS - [Utility](https://cube.fyi/utility.html#utility)

### Useful resources

- [Change the base dir for vite](https://stackoverflow.com/questions/69744253/vite-build-always-using-static-pathshttps://www.example.com) - This allowd me to solve the issue of broken links that have their base dir set to the root of the domain.
- [Host dist and src folder in one repo without overlap and deploy dist folder](https://sangsoonam.github.io/2019/02/08/using-git-worktree-to-deploy-github-pages.html) - This allowed me to have two worktrees in the same repo. One tracking the source code and the other tracking the dist folder. The worktree tracking the dist folder was used for GitHub Pages

## Author

- Frontend Mentor - [@SilvanosEric](https://www.frontendmentor.io/profile/SilvanosEric)
