# Battle #14 - ZIndex

## #79. Tambourine (99.9%)

[Link to the problem](https://cssbattle.dev/play/79)

![target](https://cssbattle.dev/targets/79.png)

```html
<div class="circle">
  <div class="c c1"></div>
  <div class="c c2"></div>
  <div class="c c3"></div>
  <div class="c c4"></div>
  <div class="c c5"></div>
  <div class="c6"></div>
  <div class="c7"></div>
</div>
<style>
  body {
    background: #6592cf;
  }
  .circle {
    position: absolute;
    top: 75;
    left: 115;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 10px solid #243d83;
  }
  .c {
    width: 10px;
    height: 10px;
    background: #243d83;
    border-radius: 50%;
    border: 10px solid #6592cf;
    box-shadow: 0 0 0 10px #243d83;
    position: absolute;
  }
  .c1 {
    top: 90;
    left: -10;
  }
  .c2 {
    top: 20;
    left: -10;
  }
  .c3 {
    top: -20;
    left: 60;
  }
  .c4 {
    top: 20;
    right: -10;
  }
  .c5 {
    top: 90;
    right: -10;
  }
  .c6 {
    width: 50px;
    height: 50px;
    border-radius: 60px 0;
    border: 11px solid #243d83;
    transform: rotate(45deg);
    position: absolute;
    top: 105;
    left: 39;
  }
  .c7 {
    width: 100px;
    height: 100px;
    background: #6592cf;
    border-radius: 50%;
    position: absolute;
    top: 125;
    left: 25;
  }
</style>
```
