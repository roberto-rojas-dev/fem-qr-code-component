# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Links

- Solution URL: [Github repository](https://github.com/roberto-rojas-dev/fem-qr-code-component/tree/main)
- Live Site URL: [Netlify website](https://rjrr-fem-qr-code-component.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned

Images have a default value of `display: inline;`, so if you put an image inside a container, it will show a small margin under itself, preventing it from fitting perfectly into its container. To avoid this issue you can set the display property to `block`.

```html
<div class="image-container">
  <img class="image" src="image.png" alt="image description">
</div>
```
```css
/* Reset */

img{
  display: block;
}

/* Layout */

.image-container {
  width: 20rem;
}

.image{
  width: 100%;
}
```

### Continued development

Improving at using semantic HTML tags and creating more accesible components

### Useful resources

- [Get rid of that small space under your images - Kevin Powell](https://youtu.be/plOl7TNc89A?si=RF2e-QfYCnTRA1PS)


## Author

- Frontend Mentor - [@roberto-rojas-dev](https://www.frontendmentor.io/profile/roberto-rojas-dev)
- GitHub - [roberto-rojas-dev
](https://github.com/roberto-rojas-dev)

## Acknowledgments

Thanks to Kevin Powell for creating such a useful content. It was very helpful to solve my problem with images. 💜
