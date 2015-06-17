# Condensed Bootstrap Grid

Packs the entire grid system into 1 Sass partial (2kb).

### Setup

Download and place `_grid.scss` inside of your Sass project. Import the grid partial and your are done.

```scss
@import "grid";
```

Configuration options within the partial are set to Bootstrap 3 defaults, but can easily be changed.

+ Gutter size
+ Number of columns
+ Breakpoints screen widths
+ Breakpoint container widths

##### Bower

```
bower install cbg
```

### Usage

Just like Bootstrap 3. Even though the compiled output does not match the bootstrap grid perfectly (combined classes with some reordering), it behaves the exact same way.

### What about the official Bootstrap Sass?

The official [Bootstrap Sass](https://github.com/twbs/bootstrap-sass) works just great but requires a little more setup if you only want the grid. This also requires you to download the entire bootstrap sass directory where as the condensed bootstrap grid is only one 4kb file.
