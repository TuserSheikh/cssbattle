# Battle #13 - Clip

## #73 - Danger Noodle

[Link to the problem](https://cssbattle.dev/play/74)

![target](https://cssbattle.dev/targets/74.png)

```html
<div class="head"></div>
<div class="long"></div>
<div class="short"></div>
<div class="long-curve one"></div>
<div class="long-curve two"></div>
<div class="long-curve three"></div>
<div class="long-curve four"></div>
<div class="long-curve five"></div>
<div class="long-curve six"></div>
<style>
  body {
    background: #191919;
  }
  .head {
    position: absolute;
    width: 50;
    height: 30;
    background: #e08027;
    top: 135;
    left: 265;
    border-radius: 13px 20px 20px 13px;
    box-shadow: 0 0 0 20px #191919;
    z-index: 5;
  }
  .head::before {
    content: "";
    width: 30;
    height: 5;
    background: #e08027;
    top: 5;
    left: -20;
    position: absolute;
    box-shadow: 0 15px #e08027;
  }
  .head::after {
    content: "";
    width: 10;
    height: 10;
    background: #191919;
    top: 2;
    right: 10;
    position: absolute;
    border-radius: 50%;
    box-shadow: 0 16px #191919;
  }
  .long {
    width: 5;
    height: 155;
    background: #e08027;
    color: #e08027;
    top: 72;
    left: 65;
    position: absolute;
    box-shadow: 15px 0, 50px 0, 65px 0, 100px 0, 115px 0;
  }
  .short {
    width: 5;
    height: 55;
    background: #e08027;
    color: #e08027;
    top: 72;
    left: 15;
    position: absolute;
    box-shadow: 15px 0, 200px 100px, 215px 100px;
  }
  .long-curve {
    width: 70;
    height: 37;
    border-radius: 50px 50px 0 0;
    position: absolute;
    box-sizing: border-box;
    border: 5px solid #e08027;
    border-bottom: 0;
  }
  .long-curve::after {
    content: "";
    position: absolute;
    z-index: 3;
    top: 10;
    left: 10;
    right: 10;
    bottom: 0;
    border-radius: 20px 20px 0 0;
    border: 5px solid #e08027;
    border-bottom: 0;
  }
  .one {
    transform: scale(-1);
    top: 123;
    left: -35;
  }
  .two {
    top: 40;
    left: 15;
  }
  .three {
    transform: scale(-1);
    top: 223;
    left: 65;
  }
  .four {
    top: 40;
    left: 115;
  }
  .five {
    transform: scale(-1);
    top: 223;
    left: 165;
  }
  .six {
    top: 140;
    left: 215;
  }
</style>
```
