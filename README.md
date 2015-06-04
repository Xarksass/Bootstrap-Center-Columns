# CenterColumns
## Description
It's a Bootstrap plugin to help you center columns and galleries.

### Compatibility
Only available with the Less version of bootstrap.
The SASS version will come soon.

## Features
### .center-column-*breakpoint*-*size*
Auto calculation of the offset needed to center a group of columns with of size of x columns.

### .center-gallery-*breakpoint*-*size*
Auto calculation of the offset needed to center the last elements of a gallery.
Limited to the maximum possible size of a column for a gallery.

### .equid-column-*breakpoint*-*size* and .equid-gallery-*breakpoint*-*size*
Same operation as for versions *center* but the columns are centered equidistantly from each others.

## Demonstration page
Check the [demonstration on codepen](http://codepen.io/disalvo_webdev/pen/XJOBdK/)

## Requirements
[Bootstrap](http://getbootstrap.com/)

## Basic Usage
### Columns of different sizes

```html
<div class="center-column-xs-9 center-column-sm-9 center-column-md-9 center-column-lg-9">
    <div class="col-xs-2 col-sm-2 col-md-2 col-lg-2">
        <p>.col-lg-2</p>
    </div>
    <div class="col-xs-5 col-sm-5 col-md-5 col-lg-5">
        <p>.col-lg-5</p>
    </div>
    <div class="col-xs-2 col-sm-2 col-md-2 col-lg-2">
        <p>.col-lg-2</p>
    </div>
</div>
```

### Columns of the same sizes

```html
<div class="center-column-xs-9 center-column-sm-9 center-column-md-9 center-column-lg-9">
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
</div>
```

You can also use *center-gallery* for multiple columns of the same size.
Example:

```html
<div class="center-gallery-xs-3">
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
    <div class="col-xs-3 col-sm-3 col-md-3 col-lg-3">
        <p>.col-lg-3</p>
    </div>
</div>
```

## More usages
To see more usages, check the [demonstration on codepen](http://codepen.io/disalvo_webdev/pen/XJOBdK/)