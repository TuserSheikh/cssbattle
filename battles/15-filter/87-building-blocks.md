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
    display: grid;
    place-items: center;
  }
  .left,
  .right {
    position: absolute;
    width: 100;
    height: 100;
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
    width: 50;
    height: 50;
    background: #1a4341;
    color: #1a4341;
    z-index: -1;
  }
  .left::before {
    right: -50;
    border-radius: 0 10px 10px 0;
    box-shadow: -20px 20px;
  }
  .right::before {
    left: -50;
    bottom: 0;
    border-radius: 10px 0 0 10px;
    box-shadow: 20px -20px;
  }
  .mid {
    width: 70;
    height: 70;
    background: #f3ac3c;
    border-radius: 10px;
  }
</style>
```
