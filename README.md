# CenterColumns
Auto calculation of the offset needed to center x columns.
Limited to the maximum possible size of a column for the number of column given.

## Demonstration page
check the [demonstration on codepen](http://codepen.io/disalvo_webdev/pen/XJOBdK/)

## Requirements
[bootstrap](http://getbootstrap.com/)

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
<div class="center-gallery-3">
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