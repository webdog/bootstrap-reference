# Bootstrap Reference

This document serves as a guide to common tags and classes in bootstrap

##Grid System
| Tag | Class | Subclass | Purpose | example-tag|
|:---:|:-----:|:--------:|:-------:|:----------:|
| div | container| -     | Fixed-width | `<div class="container">` |
| div | container | fluid | Full-width  | `<div class="container-fluid` |
| div | row      | -     | Horizontal group of columns | `<div class="row">` |
| div | col-\<breakpoint\>-[1-12]| - | Breakpoint for scaling up a layout | `<div class="col-xs-3">`|
|     |			 | xs	| Breakpoint for phones		     | `<div class="col-xs-3">`|
|     |                  | sm   | tablets                            | `<div class="col-sm-3">`|
|     |                  | md   | desktops                           | `<div class="col-md-6">`|
|     |                  | xl   | large format displays              | `<div class="col-xl-6">`|
|     |                  |[1-12]| number of colums to span on display| `<div class="col-md-2">`|

# Outlines and border
| Tag | Class | Subclass | Purpose | example-tag|
|:---:|:-----:|:--------:|:-------:|:----------:|
| div | panel | panel-default | creates a box around a container element | `<div class="panel panel-default">`
| -   | -     | panel-primary | as above, but blueish color hue          | `<div class="panel panel-primary">`
| -   | -     | panel-success | as above, but greenish color hue         | `<div class="panel panel-success">`
| -   | -     | panel-info    | as above, but light blueish color hue    | `<div class="panel panel-info">`
| -   | -     | panel-warning | as above, but yellow color hue           | `<div class="panel panel-warning">`
| -   | -     | panel-danger  | as above, but red warning hue            | `<div class="panel panel-danger">`


