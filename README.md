Font Awesome More
=================

A fork of Font Awesome with more icons added.


Usage
-----

Replace `@import "bootstrap/sprites.less"` with `@import "font-awesome-more.less"` in your main .less or bootsrap.less file. Then add the following, updating the font URLs to match your rewrites:

```javascript
@font-face {
    font-family: 'FontAwesome';
    src: url('../font/fontawesome-webfont.eot');
    src: url('../font/fontawesome-webfont.eot?#iefix') format('embedded-opentype'),
         url('../font/fontawesome-webfont.woff') format('woff'),
         url('../font/fontawesome-webfont.ttf') format('truetype'),
         url('../font/fontawesome-webfont.svgz#FontAwesomeRegular') format('svg'),
         url('../font/fontawesome-webfont.svg#FontAwesomeRegular') format('svg');
    font-weight: normal;
    font-style: normal;
}
```
