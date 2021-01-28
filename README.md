# splits

Splits was a test at doing a responsive grid (version available on here should work though).

Probably not useful in the days of flex and grid but I'll leave it here for posterity.

It uses semantic class names, and the grid is split into sixths as minimum sizes. Here's a an example of three third width divs:
```html
<div class="contain all-1/3">
  <div class="split"></div>
  <div class="split"></div>
  <div class="split"></div>
</div>
```
The container can be full page width or constrained, where it is set to margin: auto, and width:1000px (class="full-width" or class="contain"), you can change the 1000px to your hearts delight.

The width of the child elements is stated as a fraction and has to have split in there too (eg class="2/3 split" or class="1/4 split")

It comes without gutters by default, but adding the "gutters" class to the parent element will stick them in there. Here's an example of a 3/4 element and a 1/4 element with gutters:

```html
<div class="contain gutters">
  <div class="split 3/4"></div>
  <div class="split 1/4"></div>
</div>
```

