# Frontend Mentor - QR code component solution

My solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Overview

### Screenshot

![QR code component at phone width](./screenshot.jpg)

### Links

- Solution URL: [add your repo or submission link here](https://your-solution-url.com)
- Live Site URL: [add your live link here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 (`main`, `h1`, `footer`)
- CSS in its own stylesheet
- Flexbox
- `@font-face` with a variable font (Outfit)

### What I learned

- A variable font is one file that covers every weight. One `@font-face` with `font-weight: 100 900` does the job. My first try pointed at Regular and Bold files I didn't have.
- The file path in `src: url()` has to match the real folder and file name exactly, or the browser quietly falls back to `sans-serif`.
- `min-height: 100vh` with `display: flex`, `justify-content: center` and `align-items: center` centers a card both ways.
- `box-shadow` reads as x, y, blur, color.

```css
@font-face {
  font-family: "Outfit";
  src: url("./fonts/Outfit-VariableFont_wght.ttf");
  font-weight: 100 900;
}
```

### Continued development

- Folding duplicate selectors into one rule each.
- Stopping the footer from adding extra scroll under a 100vh layout.

### AI Collaboration

I used Claude when I was stuck in a few places.

## Author

- Website - [Guerz](https://guerz.lol)
- Frontend Mentor - [@gitguerz](https://www.frontendmentor.io/profile/gitguerz)