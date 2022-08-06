# Battle #19 - Spacing

## #110 - Sunrays

[Link to the problem](https://cssbattle.dev/play/110)

![target](https://cssbattle.dev/targets/110.png)

```html
<div class="l1"></div>
<div class="l2"></div>
<div class="l3"></div>
<div class="l4"></div>
<div class="l5"></div>
<div class="l6"></div>
<div class="l7"></div>
<style>
  body {
    background: #d25b70;
  }
  div {
    width: 10px;
    height: 100px;
    background: #f2e09f;
    border-radius: 10px;
    position: absolute;
  }
  .l1 {
    top: 150px;
    left: 125px;
    transform: rotate(90deg);
  }
  .l2 {
    top: 115px;
    left: 135px;
    transform: rotate(-60deg);
  }
  .l3 {
    top: 90px;
    left: 160px;
    transform: rotate(-30deg);
  }
  .l4 {
    top: 80px;
    left: 195px;
  }
  .l5 {
    top: 90px;
    right: 160px;
    transform: rotate(30deg);
  }
  .l6 {
    top: 115px;
    right: 135px;
    transform: rotate(60deg);
  }
  .l7 {
    top: 150px;
    right: 125px;
    transform: rotate(90deg);
  }
</style>
```
