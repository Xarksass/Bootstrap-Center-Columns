# Bootstrap Center Columns
## Description
It's a Bootstrap plugin to help you center columns and galleries.

**New in 3.3.0** : you can now enable or disable the features you don't need so that lighten the final compiled code!

### Compatibility
Only available with the Less version of bootstrap and so only for **Bootstrap 3.x**.
The SASS version for Bootstrap 4.x will come as soon as possible.

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
[Bootstrap 3.x](http://getbootstrap.com/)

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
### Center Gallery

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