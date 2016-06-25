# Bootstrap Reference

This doucment serves as a guide to common tags and classes in bootstrap

##Grid System
| Tag | Class | Subclass | Purpose | example-tag|
|:---:|:-----:|:--------:|:-------:|:----------:|
| div | container| -     | Fixed-width | `<div class="container">` |
| div | continer | fluid | Full-width  | `<div class="container-fluid` |
| div | row      | -     | Horizontal group of columns | `<div class="row">` |
| div | col-<breakpoint>-[1-12] | Breakpoint for scaling up a layout | `<div class="col-xs-3">`|
|     |			 | xs	| Breakpoint for phones		     | `<div class="col-xs-3">`|
|     |                  | sm   | tablets                            | `<div class="col-sm-3">`|
|     |                  | md   | desktops                           | `<div class="col-md-6">`|
|     |                  | xl   | large format displays              | `<div class="col-xl-6">`|
|     |                  |[1-12]| number of colums to span on display| `<div class="col-md-2">`|
