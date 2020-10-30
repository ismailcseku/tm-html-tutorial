# Theme Colors

This framework comes with 4 theme color variations:
```css
$theme-color1: #ff652f;
$theme-color2: #c25288;
$theme-color3: #32262c;
$theme-color4: #241b1f;
```

## Predefined theme color css classes:
There are a lot of predefined theme color classes in
```html
\assets\source\scss\colors\parts\_theme-color1.scss
\assets\source\scss\colors\parts\_theme-color2.scss
\assets\source\scss\colors\parts\_theme-color3.scss
\assets\source\scss\colors\parts\_theme-color4.scss
```

### Example:
Text Theme Color:
```css
.text-theme-colored1
.text-theme-colored2
.text-theme-colored3
.text-theme-colored4
```
BG Theme Color:
```css
.bg-theme-colored1
.bg-theme-colored2
.bg-theme-colored3
.bg-theme-colored4
```
Border Theme Color:
```css
.border-theme-colored1
.border-theme-colored2
.border-theme-colored3
.border-theme-colored4
```


###  lighter/darker bg Color
``` css
.bg-theme-colored1-lighter2 {
  background-color: lighten($theme-color1, 2%) !important;
}
.bg-theme-colored1-lighter3 {
  background-color: lighten($theme-color1, 3%) !important;
}
.bg-theme-colored1-lighter4 {
  background-color: lighten($theme-color1, 4%) !important;
}
.bg-theme-colored1-lighter5 {
  background-color: lighten($theme-color1, 5%) !important;
}
.bg-theme-colored1-lighter6 {
  background-color: lighten($theme-color1, 6%) !important;
}
.bg-theme-colored1-lighter7 {
  background-color: lighten($theme-color1, 7%) !important;
}
.bg-theme-colored1-lighter8 {
  background-color: lighten($theme-color1, 8%) !important;
}
.bg-theme-colored1-lighter9 {
  background-color: lighten($theme-color1, 9%) !important;
}
.bg-theme-colored1-darker2 {
  background-color: darken($theme-color1, 2%) !important;
}
.bg-theme-colored1-darker3 {
  background-color: darken($theme-color1, 3%) !important;
}
.bg-theme-colored1-darker4 {
  background-color: darken($theme-color1, 4%) !important;
}
.bg-theme-colored1-darker5 {
  background-color: darken($theme-color1, 5%) !important;
}
.bg-theme-colored1-darker6 {
  background-color: darken($theme-color1, 6%) !important;
}
.bg-theme-colored1-darker7 {
  background-color: darken($theme-color1, 7%) !important;
}
.bg-theme-colored1-darker8 {
  background-color: darken($theme-color1, 8%) !important;
}
.bg-theme-colored1-darker9 {
  background-color: darken($theme-color1, 9%) !important;
}
```

### Transparent bg Color
``` css
.bg-theme-colored1-transparent-9 {
  background-color: rgba($theme-color1, .90) !important;
}
.bg-theme-colored1-transparent-8 {
  background-color: rgba($theme-color1, .80) !important;
}
.bg-theme-colored1-transparent-7 {
  background-color: rgba($theme-color1, .70) !important;
}
.bg-theme-colored1-transparent-6 {
  background-color: rgba($theme-color1, .60) !important;
}
.bg-theme-colored1-transparent-5 {
  background-color: rgba($theme-color1, .50) !important;
}
.bg-theme-colored1-transparent-4 {
  background-color: rgba($theme-color1, .40) !important;
}
.bg-theme-colored1-transparent-3 {
  background-color: rgba($theme-color1, .30) !important;
}
.bg-theme-colored1-transparent-2 {
  background-color: rgba($theme-color1, .20) !important;
}
.bg-theme-colored1-transparent-1 {
  background-color: rgba($theme-color1, .10) !important;
}
.bg-theme-colored1-transparent {
  background-color: rgba($theme-color1, .50) !important;
}
```
