# Battle #15 - Filter

## #87 - Building Blocks

[Link to the problem](https://cssbattle.dev/play/87)

![target](https://cssbattle.dev/targets/87.png)

```html
<div class="left"></div>
<div class="mid"></div>
<div class="right"></div>
<style>
  body {
    background: #f3ac3c;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .left,
  .right {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #1a4341;
  }
  .left {
    left: 65;
    top: 65;
    border-radius: 10px 0 10px 10px;
  }
  .right {
    right: 65;
    bottom: 65;
    border-radius: 10px 10px 10px 0;
  }
  .left::before,
  .right::before {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #1a4341;
  }
  .left::before {
    right: -50;
    border-radius: 0 10px 10px 0;
  }
  .right::before {
    left: -50;
    bottom: 0;
    border-radius: 10px 0 0 10px;
  }
  .left::after,
  .right::after {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #1a4341;
    top: 20;
    z-index: -1;
  }
  .left::after {
    right: -20;
  }
  .right::after {
    left: -20;
    top: 20;
  }
  .mid {
    width: 70px;
    height: 70px;
    background: #f3ac3c;
    border-radius: 10px;
  }
</style>
```
