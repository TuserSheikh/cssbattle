# Battle #18 - Float

## #106 - Ryuk's Apple

[Link to the problem](https://cssbattle.dev/play/106)

![target](https://cssbattle.dev/targets/106.png)

```html
<div class="mid"></div>
<div class="apple left"></div>
<div class="apple right"></div>
<style>
  * {
    background: #000000;
  }
  .mid {
    width: 10px;
    height: 50px;
    background: #d4392d;
    position: absolute;
    left: 195;
    top: 70;
  }
  .apple {
    width: 100px;
    height: 120px;
    border-radius: 50%;
    background: #d4392d;
    position: absolute;
    top: 90;
  }
  .left {
    transform: rotate(-30deg);
    left: 120;
  }
  .right {
    transform: rotate(30deg);
    right: 120;
  }
  .right::before,
  .right::after {
    content: "";
    width: 50px;
    height: 60px;
    border-radius: 50%;
    background: #000000;
    position: absolute;
  }
  .right::before {
    top: 65;
    left: -76;
  }
  .right::after {
    top: 100;
    left: -56;
  }
</style>
```
