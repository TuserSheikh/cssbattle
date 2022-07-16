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
    background: #f3ac3c;
    display: flex;
    align-items: center;
  }
  .left {
    position: absolute;
    left: 45;
    width: 120px;
    height: 120px;
    background: #998235;
    border-radius: 50%;
  }
  .left::before {
    content: "";
    position: absolute;
    left: 40;
    top: 40;
    width: 10px;
    height: 40px;
    background: #1a4341;
    border-radius: 10px;
  }
  .left::after {
    content: "";
    position: absolute;
    left: 100;
    top: 50;
    width: 200px;
    height: 20px;
    background: #1a4341;
  }
  .mid {
    position: absolute;
    left: 115;
    width: 100px;
    height: 100px;
    background: #998235;
    border-radius: 50%;
  }
  .mid::after {
    content: "";
    position: absolute;
    left: 25;
    top: 25;
    width: 40px;
    height: 40px;
    background: #1a4341;
    border-radius: 50%;
    border: 5px solid #f3ac3c;
  }
  .right {
    position: absolute;
    left: 315;
    width: 40px;
    height: 30px;
    background: #998235;
    border-radius: 10px;
  }
  .right::before,
  .right::after {
    content: "";
    position: absolute;
    top: 8;
    left: 10;
    width: 20px;
    height: 4px;
    background: #1a4341;
    border-radius: 10px;
  }
  .right::after {
    top: 18;
  }
</style>
```
