# Notes
These are my notes as I teach myself about parallax scrolling in CSS for scrollytelling.

# Scrollytelling with position: sticky
**Resource**: [Scrollytelling with position sticky - full images](https://codepen.io/enatario/pen/jKrJpB) by Elaina Natario -- full background image + not-full-width scrolling text + full-width text at the bottom

The CSS is using SCSS (_tiny_ parenthetical next to the bigger CSS title in the CSS editor pane), which is using a pre-processor on CodePen.io, so it's probably not going to work on this native browser CSS.

>There is currently no out-of-the-box support for Sassy CSS in any browser, regardless of which Sass syntax or extension you would use. But you can openly experiment with any of the 5 pre-processors on codepen.io. Aside from that you have to install a favorite CSS pre-processor on your web server." 
> -- [FreeCodeCamp blog post](https://medium.freecodecamp.org/the-complete-guide-to-scss-sass-30053c266b23), Jan 21 2019.

The $bp, etc. are variables in SCSS (which is what I figured but wanted to research/double-check), which is why none of my "what does $ mean in css" searches turned up. In CSS that's --asdf, but --bp etc. don't seem to fix it.

**Fixed**: The code in the CSS editor on CodePen is SCSS. I want the CSS, after (I think) it's been processed. CodePen has this under the top right button `Change View` > `Direct Links` > `.css`, which opens in a new browser tab with the plain text of the regular CSS. Pasting that in between style tags and a page refresh fixed the scrollytelling into the working example.

# Sources used/gathered

## Dev tools
- [Placeholder images](http://placekitten.com/) = `http://placekitten.com/width/height` in pixels

## CSS, & then SCSS/SASS
- [Everything you need to know about CSS Variables](https://medium.freecodecamp.org/everything-you-need-to-know-about-css-variables-c74d922ea855) by FreeCodeCamp, 12 Feb 2018
- [The Complete Guide to SCSS/SASS](https://medium.freecodecamp.org/the-complete-guide-to-scss-sass-30053c266b23) by FreeCodeCamp, 21 Jan 2019
  - [Intro to SCSS for Sass Users](https://sass-lang.com/documentation/file.SCSS_FOR_SASS_USERS.html) by sass-lang.com, accessed 1 Apr 2019

## Scrollytelling with mainly CSS
- [W3Schools](https://www.w3schools.com/howto/howto_css_parallax.asp)
- [Easier scrollytelling with position sticky](https://pudding.cool/process/scrollytelling-sticky/) - The Pudding, June 2018
  - [Full code/examples](https://codepen.io/collection/XBWPqE/#) linked in article
    - [Sticky progress](https://codepen.io/snookca/pen/ZvpZYE) by Jonathan Snook -- elements sticking together would be nice for my idea of (Trumbull) lyric lines as scrolling sticking together in partial/whole verses
    - [Horizontal slide in and out effect using sticky elements](https://codepen.io/rpsthecoder/pen/LJZzRV) by Preethi Sam -- cool idea
    - [Scrollytelling with position sticky](https://codepen.io/enatario/pen/eKzxzY) by Elaina Natario -- side scrolling text + full-width text at the bottom
    - [Scrollytelling with position sticky - full images](https://codepen.io/enatario/pen/jKrJpB) by Elaina Natario -- full background image + not-full-width scrolling text + full-width text at the bottom

## Scrollytelling with mainly Javascript libraries
- [An Introduction to Scrollama.js](https://pudding.cool/process/introducing-scrollama/) - The Pudding, November 2017
  - [ ] **to-do**: work through the article & pull out sources/code for use later