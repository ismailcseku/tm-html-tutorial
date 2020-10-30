# Theme Mascot HTML Utility Classes

1. There are a lot of `utility classes` in 
``` html
assets/source/scss/scss-core/_utility-classes.scss
```

2. There are a lot of `margin padding` in 
``` html
assets/source/scss/scss-core/_custom-bootstrap-margin-padding.scss
```


3. There are a lot of data attributes in 
`js/custom.js` file:

``` js
  $('[data-tm-bg-color]').each(function() {
    $(this).css("cssText", "background-color: " + $(this).data("tm-bg-color") + " !important;");
  });
  $('[data-tm-bg-img]').each(function() {
    $(this).css('background-image', 'url(' + $(this).data("tm-bg-img") + ')');
  });
  $('[data-tm-text-color]').each(function() {
    $(this).css('color', $(this).data("tm-text-color"));
  });
  $('[data-tm-font-size]').each(function() {
    $(this).css('font-size', $(this).data("tm-font-size"));
  });
  $('[data-tm-opacity]').each(function() {
    $(this).css('opacity', $(this).data("tm-opacity"));
  });
  $('[data-tm-height]').each(function() {
    $(this).css('height', $(this).data("tm-height"));
  });
  $('[data-tm-width]').each(function() {
    $(this).css('width', $(this).data("tm-width"));
  });
  $('[data-tm-border]').each(function() {
    $(this).css('border', $(this).data("tm-border"));
  });
  
  $('[data-tm-padding]').each(function() {
    $(this).css('padding', $(this).data("tm-padding"));
  });
  $('[data-tm-padding-top]').each(function() {
    $(this).css('padding-top', $(this).data("tm-padding-top"));
  });
  $('[data-tm-padding-right]').each(function() {
    $(this).css('padding-right', $(this).data("tm-padding-right"));
  });
  $('[data-tm-padding-bottom]').each(function() {
    $(this).css('padding-bottom', $(this).data("tm-padding-bottom"));
  });
  $('[data-tm-padding-left]').each(function() {
    $(this).css('padding-left', $(this).data("tm-padding-left"));
  });

  $('[data-tm-margin]').each(function() {
    $(this).css('margin', $(this).data("tm-margin"));
  });
  $('[data-tm-margin-top]').each(function() {
    $(this).css('margin-top', $(this).data("tm-margin-top"));
  });
  $('[data-tm-margin-right]').each(function() {
    $(this).css('margin-right', $(this).data("tm-margin-right"));
  });
  $('[data-tm-margin-bottom]').each(function() {
    $(this).css('margin-bottom', $(this).data("tm-margin-bottom"));
  });
  $('[data-tm-margin-left]').each(function() {
    $(this).css('margin-left', $(this).data("tm-margin-left"));
  });
``` 

To use bg image, use this:
``` html
data-tm-bg-img="images/bg/bg1.jpg"
```

To use a Background Image in a section, use this:
``` html
<section class="bg-no-repeat bg-img-right" data-tm-bg-img="images/bg/bg1.jpg">
```
To use a Background Color in a section, use this:
``` html
<section class="bg-no-repeat bg-img-right" data-tm-bg-color="#eee">
```

To use custom margin padding, use this:
``` html
data-tm-margin-bottom="-400px"
```
