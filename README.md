# Frontend Mentor - QR Code Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

<img width="957" alt="screenshot" src="https://user-images.githubusercontent.com/36783010/201489258-bde07e36-e759-4f10-bc69-e1db852a75a1.png">

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/qr-code-component-Lexv7K_wL7)
- Live Site URL: [QR Code Component](https://qr-code-component-ans.vercel.app/)

## My process

### Built with

- HTML
- CSS
- Flexbox
- Google Fonts
- Media Queries
- Responsively App

### What I learned

Although I was able to center the main card horizontally, it was a little tricky to get it centered vertically, even though I was using the appropriate Flexbox properties. Finally, I was able to get it centered vertically using the following CSS:

```css
.main-container {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  margin: auto;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
```

### Continued development

Although I was able to use media queries successfully to achieve what I needed to for this project, I want to focus on improving the way I use media queries in future projects.

## Author

- Website - [Adolf Schmuck](https://adolfschmuck.com/)
- Frontend Mentor - [@answebdev](https://www.frontendmentor.io/profile/answebdev)
- GitHub - [@answebdev](https://github.com/answebdev)
