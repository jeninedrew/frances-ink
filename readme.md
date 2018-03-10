# [Frances Ink](https://frances.ink/) 

Check out the [case study](https://frances.ink/portfolio/frances-ink.html).

## Summary

Frances Ink's portfolio site is built with the help of Foundation, a front-end framework, and a little bit of jQuery.

The focus is on a clean presentation and improved performance. Using Sass and the BEM methodology along with semantic HTML5 resulted in improved code. Relying on Gulp made development a breeze.

* Strategy, Design and Development
* Foundation 6
* Performance
* Accessibility
* HTML, CSS, Sass, Gulp, jQuery 

<br> 

<p align="center">
  <img src ="https://frances.ink/assets/img/frances-ink/fi-work.png" />
</p>

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

## Design Highlights

###  Structure 

The site is centered around case studies. When considering how to explain Frances Ink’s focus and approach to potential clients, presenting past work was the most nuanced approach. Case studies are an opportunity to explain the thought process behind decisions while addressing general questions visitors might have.

* What has this company done in the past?
* What technologies do they work with?
* How do they approach projects?
* What is their design aesthetic?

Case study teasers appear on the front page, linking out to the full article. After the about page and basic contact page, case studies make up the bulk of the site’s content.

## Responsive Design

<p align="center">
  <img src ="https://frances.ink/assets/img/frances-ink/fi-small.png" />
</p>

### Template

The template design relies on a bold header and footer. Negative space and styled fonts do most of the work. The bold template design shifts attention to the case studies through contrast. Similarly, the large headings make the case study details pop.

### Colors

The site’s color palette is limited. Yellow is the single vibrant color and only used to highlight actionable elements. Splashes of color mostly come from case study screenshots. The toned down template sets the screenshots apart as the intended focal points of the site.

### Typography

With such stark colors, the typography determines the site’s feel. Open Sans is the primary font used throughout the site. Roboto Condensed is used as a condensed alternative. These complimentary sans serif options match the bold colors and template design.

## Technical Details

### Performance 
The site was built using Foundation, a front-end framework. Foundation provides a command-line tool to quickly set up projects with Sass and Gulp. The build process automatically does numerous performance-improving tasks.

Optimizing the site’s images requires a few extra steps. After choosing the appropriate format and size, Photoshop’s Save for Web feature results in considerable savings. Finally, images are compressed using ImageOptim.

The site is image heavy, with numerous screenshots shown in every case study and on the front page. To reduce the performance hit, images are only loaded when in the viewport. This is done with the Lazy Load Plugin for jQuery.

Connecting to Cloudflare for improved performance and security is a crucial last step. The service's content delivery network (CDN) provides access to distributed servers for faster page load. Additionally, taking advantage of Cloudflare’s Secure Sockets Layer (SSL) keeps data private.

Performance checks ensure nothing was missed. YSlow is great resource. This site got an A!

### Accessibility

Improving accessibility means removing barriers to accessing this site. This includes making the site usable for people with disabilities, people on various connections and people using a different browser or device. Accessibility is built into Foundation’s components which is a great starting point. Here are some additional accessibility best practices considered while building the site.

* Present critical information clearly and in appropriate formats
* Test in different browsers and screen sizes
* Optimize for disabled JavaScript
* Write semantic code
* Add appropriate markup
* Use contrasting colors
* Test with a screen reader like ChromeVox
* Test using a keyboard to navigate
