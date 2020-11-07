# Responsive breakpoints

All the Responsive breakpoints of Bootstrap 4 cab be found here:
https://getbootstrap.com/docs/4.0/layout/overview/#responsive-breakpoints


And is our framework, you will find it in:
``` html
assets\source\scss\scss-core\_responsive.scss
```


## All Responsive breakpoints
``` css
/*==========  Mobile First Method  ==========*/
 
// Small devices (landscape phones, 576px and up)
@include media-breakpoint-up(sm) {
}

// Medium devices (tablets, 768px and up)
@include media-breakpoint-up(md) {
}

// Large devices (desktops, 992px and up)
@include media-breakpoint-up(lg) {
}

// Extra large devices (large desktops, 1200px and up)
@include media-breakpoint-up(xl) {
}

/*==========  Non-Mobile First Method  ==========*/
 
// Large devices (desktops, less than 1200px)
@include media-breakpoint-down(lg) {
}

// Medium devices (tablets, less than 992px)
@include media-breakpoint-down(md) {
}

// Small devices (landscape phones, less than 768px)
@include media-breakpoint-down(sm) {
}

// Extra small devices (portrait phones, less than 576px)
@include media-breakpoint-down(xs) {
}

/*==========  minimum and maximum breakpoint Method  ==========*/
// Extra large devices (large desktops, 1200px and up)
//@media (min-width: 1200px) { ... }
@include media-breakpoint-only(xl) {
}

// Large devices (desktops, 992px and up)
//@media (min-width: 992px) and (max-width: 1199.98px) { ... }
@include media-breakpoint-only(lg) {
}

// Medium devices (tablets, 768px and up)
//@media (min-width: 768px) and (max-width: 991.98px) { ... }
@include media-breakpoint-only(md) {
}

// Small devices (landscape phones, 576px and up)
//@media (min-width: 576px) and (max-width: 767.98px) { ... }
@include media-breakpoint-down(sm) {
}

// Extra small devices (portrait phones, less than 576px)
//@media (max-width: 575.98px) { ... }
@include media-breakpoint-only(xs) {
}
```

