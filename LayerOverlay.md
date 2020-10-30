# Section Layer Overlay

All layer overlay classes are found at:
``` html
assets\source\scss\scss-core\_overlay.scss
```


## Standard Section with Layer Overlay
In following example, we used layer overlay theme colored1 with opacity 9 in 10. Here 9 can be from 1 to 9 variaitons.
``` html
<!-- Section: Divider -->
<section class="divider layer-overlay overlay-theme-colored1-9">
  <div class="container">
    <div class="section-content">
      <div class="row">
        <div class="col-lg-8">
          <h2 class="text-white">Quality, Affordable, Manufacturing and industrial Services</h2>
        </div>
        <div class="col-lg-4">
          <div class="tm-sc-button mt-20 text-left text-lg-right">
            <a href="#" class="btn btn-dark btn-lg text-uppercase">Discover More</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

## Here is the list of all layer overlay:

### Layer Overlay - Black
``` css
.layer-overlay {
  &.overlay-light {
    &::before {
      background-color: rgba($white-base, .40);
    }
  }
  &.overlay-lighter {
    &::before {
      background-color: rgba($white-base, .30);
    }
  }
  &.overlay-deep {
    &::before {
      background-color: rgba($white-base, .90);
    }
  }
  /* overlay-dark */
  &.overlay-dark {
    &::before {
      background-color: rgba($black-111, .85);
    }
  }
  &.overlay-dark-1 {
    &::before {
      background-color: rgba($black-111, .10);
    }
  }
  &.overlay-dark-2 {
    &::before {
      background-color: rgba($black-111, .20);
    }
  }
  &.overlay-dark-3 {
    &::before {
      background-color: rgba($black-111, .30);
    }
  }
  &.overlay-dark-4 {
    &::before {
      background-color: rgba($black-111, .40);
    }
  }
  &.overlay-dark-5 {
    &::before {
      background-color: rgba($black-111, .50);
    }
  }
  &.overlay-dark-6 {
    &::before {
      background-color: rgba($black-111, .60);
    }
  }
  &.overlay-dark-7 {
    &::before {
      background-color: rgba($black-111, .70);
    }
  }
  &.overlay-dark-8 {
    &::before {
      background-color: rgba($black-111, .80);
    }
  }
  &.overlay-dark-9 {
    &::before {
      background-color: rgba($black-111, .90);
    }
  }
}
```


### Layer Overlay - White
``` css
.layer-overlay {
  &.overlay-white {
    &::before {
      background-color: rgba($white-base, .40);
    }
  }
  &.overlay-white-1 {
    &::before {
      background-color: rgba($white-base, .10);
    }
  }
  &.overlay-white-2 {
    &::before {
      background-color: rgba($white-base, .20);
    }
  }
  &.overlay-white-3 {
    &::before {
      background-color: rgba($white-base, .30);
    }
  }
  &.overlay-white-4 {
    &::before {
      background-color: rgba($white-base, .40);
    }
  }
  &.overlay-white-5 {
    &::before {
      background-color: rgba($white-base, .50);
    }
  }
  &.overlay-white-6 {
    &::before {
      background-color: rgba($white-base, .60);
    }
  }
  &.overlay-white-7 {
    &::before {
      background-color: rgba($white-base, .70);
    }
  }
  &.overlay-white-8 {
    &::before {
      background-color: rgba($white-base, .80);
    }
  }
  &.overlay-white-9 {
    &::before {
      background-color: rgba($white-base, .90);
    }
  }
}
```



### Layer overlay Theme Colored
```css
.layer-overlay {
  /* .overlay-theme-colored1 */
  &.overlay-theme-colored1 {
    &::before {
      background-color: rgba($theme-color1, .80) !important;
    }
  }
  &.overlay-theme-colored1-1 {
    &::before {
      background-color: rgba($theme-color1, .10);
    }
  }
  &.overlay-theme-colored1-2 {
    &::before {
      background-color: rgba($theme-color1, .20);
    }
  }
  &.overlay-theme-colored1-3 {
    &::before {
      background-color: rgba($theme-color1, .30);
    }
  }
  &.overlay-theme-colored1-4 {
    &::before {
      background-color: rgba($theme-color1, .40);
    }
  }
  &.overlay-theme-colored1-5 {
    &::before {
      background-color: rgba($theme-color1, .50);
    }
  }
  &.overlay-theme-colored1-6 {
    &::before {
      background-color: rgba($theme-color1, .60);
    }
  }
  &.overlay-theme-colored1-7 {
    &::before {
      background-color: rgba($theme-color1, .70);
    }
  }
  &.overlay-theme-colored1-8 {
    &::before {
      background-color: rgba($theme-color1, .80);
    }
  }
  &.overlay-theme-colored1-9 {
    &::before {
      background-color: rgba($theme-color1, .90);
    }
  }
}
```