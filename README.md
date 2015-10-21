#gridCSS

An easily customizable grid system that won't interfere with your styles.

Row: `row`

Column Sizes: 

- `sm`: 768px and up
- `md`: 992px and up
- `lg`: 1200px and up

Widths: `1 - 12` (inclusive)

Offsets: `1 - 11` (inclusive)

Sample Syntax (this creates a column of size "medium" with a width of 3 offset by a size "medium" width 4 column): `<div class="col-md-3 col-md-offset-4`



##Demo

![grid-row picture](https://cloud.githubusercontent.com/assets/8270120/10570477/3ee2b1d2-75e9-11e5-9266-454923763105.png)

##Usage

You create a row which will be structed as any number of columns with a total column width of 12. You do this by adding the class `row`. 

You then add column classes to indicate their width. The widths range from 1-12 (inclusive). You also specify the screen width you are targeting using the `sm`, `md`, or `lg` indicator. The result will look like: `col-md-2`.

You can also offset using similar syntax: `col-lg-offset-3`. That is creating a column with an equivalent width to a large-width-3 column but is using that to push the next column to the right.


##Sample Code

```
<div class="row">
  <div class="col-md-7">
    <p>I am as wide as a col-7!<p>
  </div>
  <div class="col-md-5">
    <p>I am as wide as a col-5!<p>
  </div>
</div>

<!-- With offsets -->
<div class="row">
  <div class="col-md-5">
    <p>I am as wide as a col-5!<p>
  </div>
  <div class="col-md-5 col-offset-md-2">
    <p>I am as wide as a col-5 but offset by 2 column widths!<p>
  </div>
</div>
```

##License

[MIT license](https://github.com/dhg/Skeleton/blob/master/LICENSE.md)

😊
