# Battle #18 - Float

## #102 - One Piece

[Link to the problem](https://cssbattle.dev/play/102)

![target](https://cssbattle.dev/targets/102.png)

```html
<div class="bone b1"></div>
<div class="bone b2"></div>
<div class="bone b3"></div>
<div class="bone b4"></div>
<div class="head"></div>
<div class="teeth t1"></div>
<div class="teeth t2"></div>
<div class="teeth t3"></div>
<style>
  body {
    background: #000000;
  }
  .head {
    position: absolute;
    top: 100;
    left: 115;
    width: 150px;
    height: 100px;
    background: #ffffff;
    border-radius: 60px;
    border: 10px solid;
  }
  .head::before,
  .head::after {
    content: "";
    position: absolute;
    top: 25;
    height: 50px;
    width: 40px;
    background: #000000;
    border-radius: 50%;
  }
  .head::before {
    left: 25;
    transform: rotate(60deg);
  }
  .head::after {
    right: 25;
    transform: rotate(-60deg);
  }
  .teeth {
    position: absolute;
    top: 220;
    width: 15px;
    height: 20px;
    background: #ffffff;
  }
  .t1 {
    left: 173;
  }
  .t2 {
    left: 193;
  }
  .t3 {
    left: 213;
  }
  .bone {
    position: absolute;
    width: 20px;
    height: 18px;
    background: #ffffff;
    z-index: 4;
  }
  .bone::before,
  .bone::after {
    content: "";
    position: absolute;
    top: -20;
    height: 25px;
    width: 25px;
    background: #ffffff;
    border-radius: 50%;
  }
  .bone::before {
    left: -10;
  }
  .bone::after {
    right: -10;
  }
  .b1 {
    top: 105;
    left: 114;
    transform: rotate(-45deg);
  }
  .b2 {
    top: 105;
    right: 114;
    transform: rotate(45deg);
  }
  .b3 {
    top: 197;
    right: 114;
    transform: rotate(135deg);
  }
  .b4 {
    top: 197;
    left: 114;
    transform: rotate(-135deg);
  }
</style>
```
