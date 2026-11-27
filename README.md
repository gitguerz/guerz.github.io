<div align="center">

# QR code component

**Scan the code, then scan the source.**

![HTML5](https://img.shields.io/badge/HTML5-semantic-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-flexbox-1572B6?logo=css3&logoColor=white)
![Font](https://img.shields.io/badge/font-Outfit%20(variable)-1f2937)

[Live site](https://gitguerz.github.io/guerz.github.io/) · [The challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) · [guerz.lol](https://guerz.lol)

 <main class="page"> <!-- the main-content landmark; .page is your hook for centering -->
    <figure class="qr-card"> <!-- the card is now a figure: a self-contained unit of image plus caption -->

   <img class="qr-image" src="./images/image-qr-code.png" alt="QR code that links to the Frontend Mentor website" size="320"> <!-- QR code; alt says where it leads -->

  <figcaption> <!-- the caption for the image; it can hold the heading and text -->
  <h1 class="qr-title">Improve your front-end skills by building projects</h1> <!-- the only heading, so h1 -->

  <p class="qr-text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p> <!-- supporting text -->
  </figcaption> <!-- end caption -->

   </figure> <!-- end card -->
  </main> <!-- end main -->


</div>

## Overview

My solution to the QR code component challenge on Frontend Mentor. It's a single card with a QR code image, a heading, and a short paragraph, centered on the page and matched to the design at phone widths and up.

### Links

- Solution URL: [github.com/gitguerz/guerz.github.io](https://github.com/gitguerz/guerz.github.io)
- Live Site URL: [frontend.guerz.lol](https://frontend.guerz.lol/)
## Spec sheet

| | |
|---|---|
| Challenge | QR code component, Frontend Mentor |
| Stack | HTML and CSS only |
| Layout | Flexbox centering with `min-height: 100vh` |
| Type | Outfit, one variable font file covering weights 100 to 900 |

## Built with

- Semantic HTML5: `main`, `figure`, `figcaption`, `h1`, `footer`
- CSS in its own stylesheet, one rule per selector
- Flexbox
- `@font-face` with a variable font

## What I learned

- A variable font is one file that covers every weight, so one `@font-face` with `font-weight: 100 900` is enough. My first attempt pointed at Regular and Bold files I didn't have, and the browser quietly fell back to `sans-serif`. The Network tab in DevTools showed the problem.
- Browsers give `figure` a default side margin of 40px, so I set `margin: 0` on the card to keep it centered.
- `min-height: 100vh` with `display: flex`, `justify-content`, and `align-items` centers a card both ways.
- `box-shadow` reads as x, y, blur, color.

```css
@font-face {
  font-family: "Outfit";
  src: url("./fonts/Outfit-VariableFont_wght.ttf");
  font-weight: 100 900;
}
```

## Continued development

- Stop the footer from adding extra scroll under the 100vh layout.
- Get more comfortable choosing between `div`, `figure`, and `article`.

## AI collaboration

I used Claude as a coach. It wrote the HTML scaffold and told me which CSS rules to type, and it explained each one. I typed the CSS myself, fixed my own font path, and chose to use `figure` for the card.

## Author

- Website: [guerz.lol](https://guerz.lol)
- Frontend Mentor: https://www.frontendmentor.io/profile/gitguerz
