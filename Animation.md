# Animation Classes

All animation classes can be found at:
``` html
assets\source\scss\scss-core\parts\_animations.scss
```


## To animate a div
To animate and fade(When Visible) in a div, you can use following classes.
``` html
<!-- Section: Divider -->
  <div class="tm-animation fade-in">
  </div>
  <div class="tm-animation fade-in2">
  </div>
  <div class="tm-animation fade-in3">
  </div>
  <div class="tm-animation fade-in4">
  </div>
```

To animate and move up(When Visible) in a div, you can use following classes.
``` html
<!-- Section: Divider -->
  <div class="tm-animation move-up">
  </div>
  <div class="tm-animation move-up2">
  </div>
  <div class="tm-animation move-up3">
  </div>
  <div class="tm-animation move-up4">
  </div>
```

## Floating Objects:

Here is an example of floating objects
``` html
  <div class="tm-floating-objects d-none d-xl-block">
    <span class="floating-object-1 tm-animation-floating" data-tm-bg-img="images/photos/shape1.png" data-tm-width="224" data-tm-height="244" data-tm-top="10%" data-tm-opacity="0.8"></span>
    <span class="floating-object-2 tm-animation-scaling" data-tm-bg-img="images/photos/shape2.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
    <span class="floating-object-3 tm-animation-flicker" data-tm-bg-img="images/photos/shape3.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
    <span class="floating-object-4 tm-animation-slide-horizontal" data-tm-bg-img="images/photos/shape4.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
  </div>
```


And this is how you have to put it into a section:
``` html
<section>
  <div class="container">
    <div class="row">
    </div>
  </div>

  <!-- floating objects -->
  <div class="tm-floating-objects d-none d-xl-block">
    <span class="floating-object-1 tm-animation-floating" data-tm-bg-img="images/photos/shape1.png" data-tm-width="224" data-tm-height="244" data-tm-top="10%" data-tm-opacity="0.8"></span>
    <span class="floating-object-2 tm-animation-spin" data-tm-bg-img="images/photos/shape2.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
    <span class="floating-object-3 tm-animation-flicker" data-tm-bg-img="images/photos/shape3.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
    <span class="floating-object-4 tm-animation-slide-horizontal" data-tm-bg-img="images/photos/shape4.png" data-tm-width="460" data-tm-height="427" data-tm-top="55%" data-tm-right="-5%" data-tm-opacity="0.8"></span>
  </div>
</section>
```

