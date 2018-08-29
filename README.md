# Project RWD Static Webpage

## Content

Static webpage to practice responsive web design

[Github pages](https://mnap00.github.io/project-rwd-static-page/)

This one is imported from external editor and will be used as a template for the project. The webpage was written in HTML5 and CSS3 only. No JS events.

CSS is a horrible mess. Tag and class selectors are mixed and written without prior plan.

HTML is acceptable, since I did not plan to use JS frameworks nor libraries for rendering.

Npm scripts are superfluous. Some of them was made for Node.js projects, some for single page apps written with Webpack. Most of them can be removed. The same is with packages.

## Todo
* Clean up `package.json`:
  - fix npm scripts; make it simple, for webpages only, no Node.js, no Webpack scripts
  - remove not needed packages; only linters, preprocessors and watchers should stay
  - revise npm shell packages
* Clean up CSS: remove tag selectors wherever possible and use classes (e.g. BEM)
* Make responsive, dropdown navigation menu
