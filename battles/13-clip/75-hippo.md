# Battle #13 - Clip

## #75 - Hippo

[Link to the problem](https://cssbattle.dev/play/75)

![target](https://cssbattle.dev/targets/75.png)

```html
<div class="ear left"></div>
<div class="ear right"></div>
<div class="mid"></div>
<div class="bottom"></div>
<style>
  body {
    background: #191919;
  }
  .ear {
    background: #000000;
    position: absolute;
    top: 70;
    width: 10px;
    height: 20px;
    border-radius: 50%;
    border: 5px solid #fe5f55;
  }
  .left {
    left: 150;
    transform: rotate(-45deg);
  }
  .right {
    right: 150;
    transform: rotate(45deg);
  }
  .mid {
    position: absolute;
    top: 75;
    left: 135;
    width: 130px;
    height: 100px;
    border-radius: 60px 60px 0 0;
    background: #fe5f55;
  }
  .mid::before,
  .mid::after {
    content: "";
    position: absolute;
    top: 50;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #000000;
  }
  .mid::before {
    left: 25;
  }
  .mid::after {
    right: 25;
  }
  .bottom {
    position: absolute;
    top: 145;
    left: 125;
    width: 150px;
    height: 100px;
    border-radius: 55px 55px 44px 44px;
    background: #a64942;
  }
  .bottom::before,
  .bottom::after {
    content: "";
    position: absolute;
    top: 20;
    width: 20px;
    height: 30px;
    border-radius: 50%;
    background: #000000;
  }
  .bottom::before {
    left: 25;
    transform: rotate(45deg);
  }
  .bottom::after {
    right: 25;
    transform: rotate(-45deg);
  }
</style>
```
