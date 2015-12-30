# splits

Splits is a responsive grid under development (version available on here will work though, just that more features may be added).

It uses semantic class names, and the grid is split into sixths. Here's a an example of three third width divs:
```html
<div class="contain all-1/3">
  <div class="split"></div>
  <div class="split"></div>
  <div class="split"></div>
</div>
```
It's full page width or constrained to margin auto container (class="full-width" or class="contain").

The width of the child elements is stated as a fraction (eg class="2/3" or class="1/4")

Comes default without gutters. but adding the "gutters" class to the parent element will stick them in there. Here's an example of a 3/4 element and a 1/4 element with gutters:

```html
<div class="contain gutters">
  <div class="split 3/4"></div>
  <div class="split 1/4"></div>
</div>
```

You can check out more of the syntax and some of the cooler features over at http://splitsframework.com/syntax

If anyone is up for collaborating message me!

Cheers

Bob
