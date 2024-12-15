# Public Landing Page

This is the public landing page. It is a simple page that provides links to My Github, Codepen, and LinkedIn.

## File Structure

├── README.md
├── astro.config.mjs
├── dist
│ ├── \_astro
│ │ ├── hoisted.BCTGVcJ4.js
│ │ └── index.BKOzDR2g.css
│ ├── favicon.svg
│ ├── fonts
│ │ ├── ChivoMono[wght].woff
│ │ └── SegoeAlt.woff
│ └── index.html
├── package-lock.json
├── package.json
├── public
│ ├── android-chrome-192x192.png
│ ├── android-chrome-512x512.png
│ ├── apple-touch-icon.png
│ ├── assets
│ ├── favicon-16x16.png
│ ├── favicon-32x32.png
│ ├── favicon.svg
│ ├── fonts
│ │ ├── ChivoMono[wght].woff
│ │ └── SegoeAlt.woff
│ └── js
├── src
│ ├── components
│ │ ├── BubbleBackdrop.astro
│ │ ├── LandingPage.astro
│ │ └── button.astro
│ ├── env.d.ts
│ ├── js
│ │ ├── modules
│ │ │ ├── cards.js
│ │ │ ├── light-rays.js
│ │ │ └── liquidLamp.js
│ │ └── remove-debut-attrs.js
│ ├── layouts
│ │ └── BaseLayout.astro
│ ├── pages
│ │ └── index.astro
│ ├── scss
│ │ ├── global
│ │ │ ├── components
│ │ │ ├── fonts.scss
│ │ │ ├── global.scss
│ │ │ ├── index.scss
│ │ │ ├── layout.scss
│ │ │ ├── reset.scss
│ │ │ └── theme.scss
│ │ ├── mixins
│ │ │ ├── breakpoints.scss
│ │ │ ├── colors.scss
│ │ │ └── typography.scss
│ │ └── modules
│ │ ├── bubbles.scss
│ │ └── landing.scss
│ └── styles
│ └── assets
│ └── css
├── tailwind.config.mjs
└── tsconfig.json

Figured this might be useful

## issues

### FIXED

I accidentally made it only viewable on 1440px and lower at first using overflow
hidden on the body, this prevented the user from scrolling to see the rest of the page
if the content grew beyond the viewport. I fixed that issue but now the page sucks on
lower resolutions, I will fix this later, i have to restructure the dom to do that I think. a couple divs like to stretch the page a bunch with how theyre animated.

# Sources:

[Chivo](https://fonts.google.com/specimen/Chivo)
[Segoe](https://fonts.google.com/specimen/Segoe+UI)
[Rays](https://codepen.io/creativeocean/pen/ZEEOxmK)
[Bubbles](https://codepen.io/hbagency/pen/Nrdbdp)
[Fog](https://s3-us-west-2.amazonaws.com/s.cdpn.io/721952/vanta.fog.min.js)
[Dependencies](https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.3/TweenMax.min.js)
[MoreDependencies](https://cdnjs.cloudflare.com/ajax/libs/three.js/109/three.min.js)
