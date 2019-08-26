# Flexbox Grid SCSS Flavour 📈

This is a SCSS version of the amazing [FlexboxGrid](http://flexboxgrid.com) by [https://twitter.com/dam](https://twitter.com/dam) 💕.

Give all your thanks you to him because he made something really amazing with this.

Made because I really loved the grid system but wanted to use it within some projects that use SCSS.

## How to use it

All you gotta do is create some variables

```scss
$outer-margin: 2rem;
$gutter-width: 1rem;
$gutter-compensation: ($gutter-width * 0.5) * -1;
$half-gutter-width: $gutter-width * 0.5;
$xl: 1200px;
$lg: 996px;
$md: 768px;
$sm: 544px;
$columns: 12;
```

Write some markup!

```html
<div class="container">
  <div class="row">
    <div class="col-md-6 col-sm-4">First Column</div>
    <div class="col-md-6 col-sm-4 col-sm-offset-4"> Second Column</div>
  </div>
</div>
```

More examples of usage [here](https://codepen.io/drewminns/pen/eYOvoPo).
