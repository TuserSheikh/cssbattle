# Battle #19 - Spacing

## #112. Chevron

[Link to the problem](https://cssbattle.dev/play/112)

![target](https://cssbattle.dev/targets/112.png)

```html
<div class="bar"></div>
<div class="mid one"></div>
<div class="mid two"></div>
<div class="mid three"></div>
<div class="bar right"></div>
<style>
  body {
    background: #6592cf;
    display: flex;
    justify-content: center;
  }
  .bar {
    background: #293d7e;
    width: 39px;
    height: 85px;
    border-left: none;
    border-top: none;
    position: absolute;
    left: 128;
    top: 50;
    transform: skew(51.5deg);
    box-shadow: -63px 50px #293d7e, -126px 100px #293d7e;
  }
  .right {
    transform: skew(-51.5deg);
    left: 233;
    box-shadow: 63px 50px #293d7e, 126px 100px #293d7e;
  }
  .mid {
    position: absolute;
    width: 0;
    height: 0;
    border-top: 20px solid #293d7e;
    border-left: 25px solid transparent;
    border-right: 25px solid transparent;
  }
  .one {
    top: 130;
  }
  .two {
    top: 180;
  }
  .three {
    top: 230;
  }
</style>
```
