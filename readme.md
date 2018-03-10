# [Frances Ink](https://frances.ink/) 

Check out the [case study](https://frances.ink/portfolio/frances-ink.html).

Frances Ink's portfolio site is built with the help of Foundation, a front-end framework, and a little bit of jQuery.

The focus is on a clean presentation and improved performance. Using Sass and the BEM methodology along with semantic HTML5 resulted in improved code. Relying on Gulp made development a breeze.

![](images/table 1-1.png?raw=true)

<div style="text-align:center"><img src ="https://frances.ink/assets/img/frances-ink/fi-work.png" /></div>

![site rendered on small screen](https://frances.ink/assets/img/frances-ink/fi-small.png?raw=true "site rendered on small screen")

https://github.com/jeninedrew/frances-ink/blob/master/src/assets/img/frances-ink/fi-small.png

## ZURB Template

The ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites) is a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Lazy Load Plugin for JQuery

[Lazy Load](https://appelsiini.net/projects/lazyload/) delays loading of images.

- Makes the page load faster
- Potentially reduces server load

## Getting Started

For development, using [Foundation CLI](https://github.com/zurb/foundation-cli)...

```bash
foundation watch
```
To create a production build...

```bash
foundation build
```
