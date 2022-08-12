# Battle #20 - Hover

## #120 - Tank

[Link to the problem](https://cssbattle.dev/play/120)

![target](https://cssbattle.dev/targets/120.png)

```html
<div class="top"></div>
<div class="mid"></div>
<div class="right"></div>
<div class="tank"></div>
<style>
  body {
    margin: 0;
    border: 20px solid #54c144;
    background: #000;
  }
  div {
    position: absolute;
    background: #c74e4e;
  }
  .top {
    width: 80;
    height: 40;
    top: 60;
    left: 60;
    box-shadow: 120px 0 #c74e4e;
  }
  .mid {
    width: 200;
    height: 40;
    top: 140;
    left: 60;
  }
  .right {
    width: 40;
    height: 180;
    top: 60;
    left: 300;
  }
  .tank {
    background: #54c144;
    top: 205;
    left: 70;
    width: 20;
    height: 30;
  }
  .tank::before {
    content: "";
    width: 40;
    height: 10;
    background: #54c144;
    position: absolute;
    left: -10;
    top: -5;
    box-shadow: 0 30px #54c144, 10px 15px #54c144;
  }
  .tank::after {
    content: "";
    height: 10;
    width: 10;
    background: #fff;
    position: absolute;
    right: -40;
    top: 10;
    box-shadow: 20px 0 #fff;
  }
</style>
```
