# Battle #20 - Hover

## #117 - Arineo

[Link to the problem](https://cssbattle.dev/play/117)

![target](https://cssbattle.dev/targets/117.png)

```html
<div class="a left"></div>
<div class="a right"></div>
<div class="tick left"></div>
<div class="tick right"></div>
<div class="circle"></div>
<style>
  div {
    position: absolute;
  }
  .a {
    top: 60px;
    width: 44px;
    height: 180px;
    background: #2e2926;
  }
  .a.left {
    left: 134px;
    transform: skewX(-25deg);
  }
  .a.right {
    left: 222px;
    transform: skewX(25deg);
  }
  .tick {
    top: 60px;
    background: #0088ca;
    box-shadow: 0 11px #fff, 0 -11px #fff;
  }
  .tick.left {
    width: 80px;
    height: 28px;
    top: 50%;
    left: 120px;
    transform: skewY(45deg);
  }
  .tick.right {
    width: 120px;
    height: 28px;
    top: 43%;
    left: 200px;
    transform: skewY(-45deg);
  }
  .circle {
    width: 22px;
    height: 22px;
    border-radius: 50%;
    background: #0088ca;
    top: 139px;
    left: 189px;
  }
</style>
```
