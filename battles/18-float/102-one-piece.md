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
<div class="teeth"></div>
<style>
  body {
    background: #000;
  }
  div {
    position: absolute;
    background: #fff;
  }
  .head {
    top: 100px;
    left: 115px;
    width: 150px;
    height: 100px;
    border-radius: 60px;
    border: 10px solid;
  }
  .head::before,
  .head::after {
    content: "";
    position: absolute;
    top: 25px;
    height: 50px;
    width: 40px;
    background: #000;
    border-radius: 50%;
  }
  .head::before {
    left: 25px;
    transform: rotate(60deg);
  }
  .head::after {
    right: 25px;
    transform: rotate(-60deg);
  }
  .teeth {
    top: 220px;
    width: 15px;
    height: 20px;
    background: #fff;
    left: 173px;
    box-shadow: 20px 0 #fff, 40px 0 #fff;
  }
  .bone {
    width: 20px;
    height: 18px;
  }
  .bone::before,
  .bone::after {
    content: "";
    position: absolute;
    top: -20px;
    height: 25px;
    width: 25px;
    background: #fff;
    border-radius: 50%;
  }
  .bone::before {
    left: -10px;
  }
  .bone::after {
    right: -10px;
  }
  .b1 {
    top: 105px;
    left: 114px;
    transform: rotate(-45deg);
  }
  .b2 {
    top: 105px;
    right: 114px;
    transform: rotate(45deg);
  }
  .b3 {
    top: 197px;
    right: 114px;
    transform: rotate(135deg);
  }
  .b4 {
    top: 197px;
    left: 114px;
    transform: rotate(-135deg);
  }
</style>
```
