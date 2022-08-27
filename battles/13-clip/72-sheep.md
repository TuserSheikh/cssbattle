# Battle #13 - Clip

## #72 - Sheep

[Link to the problem](https://cssbattle.dev/play/72)

![target](https://cssbattle.dev/targets/72.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="four"></div>
<div class="five"></div>
<div class="six"></div>
<div class="seven"></div>
<div class="eight"></div>
<div class="face"></div>
<style>
  body {
    background: #243d83;
  }
  div {
    width: 60;
    height: 50;
    background: #6592cf;
    border-radius: 50%;
    position: absolute;
  }
  .one {
    top: 65;
    left: 170;
  }
  .two {
    top: 85;
    left: 210;
    transform: rotate(45deg);
  }
  .three {
    top: 125;
    left: 230;
    transform: rotate(90deg);
  }
  .four {
    top: 165;
    left: 210;
    transform: rotate(135deg);
  }
  .five {
    top: 185;
    left: 170;
  }
  .six {
    top: 165;
    left: 130;
    transform: rotate(-135deg);
  }
  .seven {
    top: 125;
    left: 110;
    transform: rotate(90deg);
  }
  .eight {
    top: 85;
    left: 130;
    transform: rotate(-45deg);
  }
  .face {
    background: #243d83;
    width: 60;
    height: 40;
    border-radius: 0 0 50px 50px;
    top: 135;
    left: 170;
    color: #6592cf;
    box-shadow: 20px 0, -20px 0, 0 20px;
  }
  .face::after {
    content: "";
    width: 10;
    height: 10;
    border-radius: 50%;
    background: #6592cf;
    position: absolute;
    top: -5;
    left: 15;
    box-shadow: 20px 0;
  }
</style>
```
