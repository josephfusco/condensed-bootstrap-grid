# Condensed Bootstrap Grid

A fully configurable & self contained grid system based on Bootstrap 3.

## Setup

Download and place `_grid.scss` inside of your Sass project & import the grid partial.

```scss
@import "grid";
```

## Usage

The default classnames generated and markup are identical to Bootstrap 3, however, [nearly everything is configurable](#options).

## Options

|Option 		  	|Type	|Default		|Description				   		|
|---				|---	|---			|---							|
|`$cbg__total-grid-cols`	|Number	|12   			|Total number of grid columns  				|
|`$cbg__gutter`			|Length	|15px			|Size of the gutters between columns			|
|`$cbg__namespace`		|String	|none			|Adds a namespace before classnames			|
|`$cbg__name--col`   		|String	|"col"			|Text generated in classname				|
|`$cbg__name--pull`   		|String	|"pull"			|Text generated in classname				|
|`$cbg__name--push`   		|String	|"push"			|Text generated in classname				|
|`$cbg__name--offset`  		|String	|"offset"		|Text generated in classname				|
|`$cbg__name--clearfix`		|String	|"clearfix"		|Text generated in classname				|
|`$cbg__name--container`	|String	|"container"		|Text generated in classname				|
|`$cbg__name--container-fluid`	|String	|"container-fluid"	|Text generated in classname				|
|`$cbg__breakpoints`		|Map	|Bootstrap 3 defaults	|[See next section](#breakpoints)			|

### Breakpoints

Breakpoints can be configured in a separate option. The defaults are set to Bootstrap 3 defaults grid dimensions.

Simply override the Sass map `cbg__breakpoints`.

```scss
// Generated string for classname: ($min-screen-width, $container-width)
$cbg__breakpoints: (
	xs: (0px, 100%),
	sm: (768px, 750px),
	md: (992px, 970px),
	lg: (1200px, 1170px)
)
```

### What about the official Bootstrap Sass?

The official [Bootstrap Sass](https://github.com/twbs/bootstrap-sass) works just great but requires a little more setup if you only want the grid. This also requires you to download the entire bootstrap sass directory where as the condensed bootstrap grid is only one small file.

### Acknowledgement

[Bootstrap](http://getbootstrap.com/)
