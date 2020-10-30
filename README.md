# Theme Mascot HTML Utility Classes

1. There are a lot of `utility classes` in 
``` html
assets/source/scss/scss-core/_utility-classes.scss
```

2. There are a lot of `margin padding` in 
``` html
assets/source/scss/scss-core/_custom-bootstrap-margin-padding.scss
```

## Data Attributes

There are a lot of data attributes in 
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

To use custom font size, use this:
``` html
data-tm-font-size="3rem"
data-tm-font-size="48px"
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

## BG Image Classes

There are a lot of predefined bg image position, repeat class in `_utility-classes.scss` file

``` css
.no-bg {
  background: none !important;
}

@include media-breakpoint-down(lg) {
  .lg-no-bg {
    background: none !important;
  }
}
@include media-breakpoint-down(md) {
  .md-no-bg {
    background: none !important;
  }
}
@include media-breakpoint-down(sm) {
  .sm-no-bg {
    background: none !important;
  }
}
@include media-breakpoint-down(xs) {
  .xs-no-bg {
    background: none !important;
  }
}

.bg-no-repeat, .bg-img-no-repeat {
  background-repeat: no-repeat !important;
}
.bg-img-fixed {
  background-attachment: fixed !important;
}
.bg-img-cover {
  background-size: cover !important;
}

.bg-img-center {
  background-position: center !important;
}
.bg-img-center-top {
  background-position: center top !important;
}
.bg-img-center-bottom {
  background-position: center bottom !important;
}


.bg-img-left {
  background-position: left !important;
}
.bg-img-left-top {
  background-position: left top !important;
}
.bg-img-left-bottom {
  background-position: left bottom !important;
}


.bg-img-right {
  background-position: right !important;
}
.bg-img-right-top {
  background-position: right top !important;
}
.bg-img-right-bottom {
  background-position: right bottom !important;
}
```

Example:

``` html
<section class="bg-no-repeat bg-img-right" data-tm-bg-img="images/bg/bg1.jpg">
```

## Standard Section with Title and content
``` html
<section id="sectionID_if_Needed">
  <div class="container">
    <div class="row">
      <!-- Section Title -->
      <div class="section-title">
        <div class="col-md-12">
          ...          ...          ...
        </div>
      </div>
      <!-- Section Content -->
      <div class="section-content">
        <div class="col-md-12">
          ...          ...          ...
        </div>
      </div>
    </div>
  </div>
</section>
```

## Standard Call to Action Divider
``` html
<!-- Section: Divider -->
<section class="bg-theme-colored1">
  <div class="container pb-70 pt-70">
    <div class="section-content">
      <div class="row">
        <div class="col-lg-8">
          <h2 class="text-white text-uppercase font-size-48">Quality, Affordable, Manufacturing and industrial Services</h2>
        </div>
        <div class="col-lg-4">
          <div class="tm-sc-button mt-20 text-left text-lg-right">
            <a href="#" class="btn btn-dark btn-lg text-uppercase"> Discover More </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

