# Battle #18 - Float

## #105 - Ryuk

[Link to the problem](https://cssbattle.dev/play/105)

![target](https://cssbattle.dev/targets/105.png)

```html
<div class="top"></div>
<div class="eye eye-left"></div>
<div class="eye eye-right"></div>
<div class="circle c-left"></div>
<div class="circle c-right"></div>
<style>
  body {
    margin: 0;
    background: #bac7ce;
  }
  .top {
    width: 200px;
    height: 200px;
    background: #475862;
    transform: rotate(45deg);
    position: absolute;
    left: 100;
    top: -150;
  }
  .eye {
    width: 120px;
    height: 120px;
    background: #000000;
    border-radius: 0 50%;
    position: absolute;
    top: 130;
  }
  .eye-left {
    transform: rotate(-15deg);
    left: 30;
  }
  .eye-right {
    transform: rotate(-75deg);
    right: 30;
  }
  .circle {
    width: 100px;
    height: 100px;
    background: #5a6042;
    border-radius: 50%;
    position: absolute;
    top: 140;
    overflow: hidden;
  }
  .c-left {
    left: 40;
  }
  .c-right {
    right: 40;
  }
  .circle::before {
    content: "";
    width: 100px;
    height: 100px;
    background: #868a64;
    border-radius: 50%;
    position: absolute;
    top: 15;
  }
  .circle::after {
    content: "";
    width: 30px;
    height: 30px;
    background: #4e2b24;
    border-radius: 50%;
    position: absolute;
    top: 30;
    left: 30;
    border: 5px solid #000000;
  }
</style>
```
