# Battle #14 - ZIndex

## #78 - Ukulele

[Link to the problem](https://cssbattle.dev/play/78)

![target](https://cssbattle.dev/targets/78.png)

```html
<div class="left"></div>
<div class="mid"></div>
<div class="right"></div>
<style>
  body {
    background: #F3AC3C;
    display: flex;
    align-items: center;
  }
  div {
    position: absolute;
    background: #998235;
  }
  .left {
    left: 45;
    width: 120;
    height: 120;
    border-radius: 50%;
  }
  .left::before {
    content: '';
    position: absolute;
    left: 40;
    top: 40;
    width: 10;
    height: 40;
    background: #1A4341;
    border-radius: 10px;
  }
  .left::after {
    content: '';
    position: absolute;
    left: 100;
    top: 50;
    width: 200;
    height: 20;
    background: #1A4341;
  }
  .mid {
    left: 115;
    width: 100;
    height: 100;
    border-radius: 50%;
  }
  .mid::after {
    content: '';
    position: absolute;
    left: 25;
    top: 25;
    width: 40;
    height: 40;
    background: #1A4341;
    border-radius: 50%;
    border: 5px solid #F3AC3C;
  }
  .right {
    left: 315;
    width: 40;
    height: 30;
    border-radius: 10px;
  }
  .right::after {
    content: '';
    position: absolute;
    top: 8;
    left: 10;
    width: 20;
    height: 4;
    background: #1A4341;
    border-radius: 10px;
    box-shadow: 0 10px #1A4341;
  }
</style>
</style>
```
