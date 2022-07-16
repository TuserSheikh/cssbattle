# Battle #14 - ZIndex

## #77 - Notes

[Link to the problem](https://cssbattle.dev/play/77)

![target](https://cssbattle.dev/targets/77.png)

```html
<div class="left"></div>
<div class="right"></div>
<div class="extra"></div>
<style>
  body {
    background: #191919;
  }
  .left,
  .right {
    position: absolute;
    top: 90;
    left: 95;
    width: 60px;
    height: 90px;
    border: 10px solid #fe5f55;
    border-bottom: 0;
  }
  .right {
    left: 235;
    border-left-color: #a64942;
    border-top-color: #a64942;
  }
  .left::before,
  .right::before,
  .left::after,
  .right::after {
    content: "";
    bottom: -20;
    width: 50px;
    height: 40px;
    border-radius: 50%;
    position: absolute;
    background: #fe5f55;
  }
  .left::before {
    left: -50;
  }
  .left::after,
  .right::after {
    left: 20;
  }
  .right::before {
    background: #a64942;
    left: -50;
  }
  .extra {
    position: absolute;
    top: 90;
    left: 305;
    width: 30px;
    height: 10px;
    border: 10px solid #fe5f55;
    border-right: 0;
    box-shadow: -30px 0 0 0 #191919;
  }
</style>
```
