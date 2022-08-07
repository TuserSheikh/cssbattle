# Battle #19 - Spacing

## #112. Chevron

[Link to the problem](https://cssbattle.dev/play/112)

![target](https://cssbattle.dev/targets/112.png)

```html
<div class="bar"></div>
<div class="mid"></div>
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
    position: absolute;
    left: 128px;
    top: 50px;
    transform: skew(51.5deg);
    box-shadow: -63px 50px #293d7e, -126px 100px #293d7e;
  }
  .right {
    transform: skew(-51.5deg);
    left: 233px;
    box-shadow: 63px 50px #293d7e, 126px 100px #293d7e;
  }
  .mid {
    position: absolute;
    border-top: 20px solid #293d7e;
    border-left: 25px solid transparent;
    border-right: 25px solid transparent;
    top: 130px;
    filter: drop-shadow(0 50px #293d7e) drop-shadow(0 50px #293d7e);
  }
</style>
```
