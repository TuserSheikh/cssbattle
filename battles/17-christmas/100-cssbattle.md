# Battle #17 - Chrismas

## #100 - CSSBattle

[Link to the problem](https://cssbattle.dev/play/100)

![target](https://cssbattle.dev/targets/100.png)

```html
<div class="outer"></div>
<div class="inner"></div>
<div class="sword left">
  <div class="point"></div>
  <div class="blade"></div>
  <div class="guard"></div>
  <div class="grip"></div>
</div>
<div class="sword">
  <div class="point"></div>
  <div class="blade"></div>
  <div class="guard"></div>
  <div class="grip"></div>
</div>
<style>
  body {
    background: #14313e;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .outer {
    width: 224px;
    height: 100px;
    background: #ffdf00;
    border-radius: 20px;
    border: 25px solid #ffdf00;
    position: relative;
  }
  .outer::before {
    content: "";
    position: absolute;
    top: 30;
    left: -35;
    width: 294px;
    height: 40px;
    background: #ffdf00;
    border-radius: 5px;
  }
  .outer::after {
    content: "";
    position: absolute;
    width: 224px;
    height: 100px;
    background: #14313e;
    border-radius: 10px;
  }
  .inner {
    position: absolute;
    width: 194px;
    height: 100%;
    background: #14313e;
  }
  .point {
    position: absolute;
    top: 71;
    left: 127;
    width: 21;
    height: 21;
    background: #ffdf00;
  }
  .blade {
    position: absolute;
    top: 60;
    left: 166;
    transform: rotate(-45deg);
    width: 30px;
    height: 150;
    background: #ffdf00;
    border-left: 10px solid #14313e;
    border-right: 10px solid #14313e;
  }
  .guard {
    position: absolute;
    top: 175;
    left: 200;
    transform: rotate(-45deg);
    width: 80px;
    height: 20px;
    background: #ffdf00;
  }
  .grip {
    position: absolute;
    top: 182;
    left: 250;
    transform: rotate(-45deg);
    width: 20px;
    height: 44px;
    background: #ffdf00;
    border-radius: 0 0 7px 7px;
  }
  .left {
    transform: rotate(90deg);
    position: absolute;
    top: -56;
    left: 345;
  }
</style>
```
