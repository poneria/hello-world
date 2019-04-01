# Notes
These are my notes as I teach myself about parallax scrolling in CSS for scrollytelling.

# Scrollytelling with position: sticky
**Resource**: [Scrollytelling with position sticky - full images](https://codepen.io/enatario/pen/jKrJpB) by Elaina Natario -- full background image + not-full-width scrolling text + full-width text at the bottom

The CSS is using SCSS (_tiny_ parenthetical next to the bigger CSS title in the CSS editor pane), which is using a pre-processor on CodePen.io, so it's probably not going to work on this native browser CSS.

>There is currently no out-of-the-box support for Sassy CSS in any browser, regardless of which Sass syntax or extension you would use. But you can openly experiment with any of the 5 pre-processors on codepen.io. Aside from that you have to install a favorite CSS pre-processor on your web server." 
> -- [FreeCodeCamp blog post](https://medium.freecodecamp.org/the-complete-guide-to-scss-sass-30053c266b23), Jan 21 2019.

The $bp, etc. are variables in SCSS (which is what I figured but wanted to research/double-check), which is why none of my "what does $ mean in css" searches turned up. In CSS that's --asdf, but --bp etc. don't seem to fix it.

# Sources used/gathered

## Dev tools
- [Placeholder images](http://placekitten.com/) = `http://placekitten.com/width/height` in pixels

## with mainly CSS
- [W3Schools](https://www.w3schools.com/howto/howto_css_parallax.asp)
- [Easier scrollytelling with position sticky](https://pudding.cool/process/scrollytelling-sticky/) - The Pudding, June 2018
  - [Full code/examples](https://codepen.io/collection/XBWPqE/#) linked in article
    - [Sticky progress]9https://codepen.io/snookca/pen/ZvpZYE) by Jonathan Snook -- elements sticking together would be nice for my idea of (Trumbull) lyric lines as scrolling sticking together in partial/whole verses
    - [Horizontal slide in and out effect using sticky elements](https://codepen.io/rpsthecoder/pen/LJZzRV) by Preethi Sam -- cool idea
    - [Scrollytelling with position sticky](https://codepen.io/enatario/pen/eKzxzY) by Elaina Natario -- side scrolling text + full-width text at the bottom
    - [Scrollytelling with position sticky - full images](https://codepen.io/enatario/pen/jKrJpB) by Elaina Natario -- full background image + not-full-width scrolling text + full-width text at the bottom
      - [ ] study this for Trumbull lyrics scroll --> HTML + CSS only

## with mainly Javascript libraries
- [An Introduction to Scrollama.js](https://pudding.cool/process/introducing-scrollama/) - The Pudding, November 2017
  - [ ] **to-do**: work through the article & pull out sources/code for use later