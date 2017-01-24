# Condensed Bootstrap Grid

Packs the entire version 3 grid system into tiny Sass partial.

### Setup

Download and place `_grid.scss` inside of your Sass project.

Import the grid partial.

```scss
@import "grid";
```

Grid is already set with Bootstrap 3 defaults, but can easily be changed.

####Changing Defaults

Define values in your _config.scss.
For example if we wanted a 5px gutter, 24 columns, and an additional `xl` breakpoint we would do the following.

```scss
// Gutter size
$gutter: 5px;

// Number of columns
$total-grid-cols: 24;

// Breakpoint name: $min-screen-width, $container-width
$breakpoints: (
	xs: (0px, 100%),
	sm: (768px, 750px),
	md: (992px, 970px),
	lg: (1200px, 1170px),
	xl: (1300px, 1270px)
);
```

### Usage

Just like Bootstrap 3.

### What about the official Bootstrap Sass?

The official [Bootstrap Sass](https://github.com/twbs/bootstrap-sass) works just great but requires a little more setup if you only want the grid. This also requires you to download the entire bootstrap sass directory where as the condensed bootstrap grid is only one small file.

### Acknowledgement

[Bootstrap](http://getbootstrap.com/), Copyright 2011-2015 Twitter, Inc.
