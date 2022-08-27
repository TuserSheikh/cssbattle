# Battle #13 - Clip

## #73 - Happy Tiger

[Link to the problem](https://cssbattle.dev/play/73)

![target](https://cssbattle.dev/targets/73.png)

```html
<div class="ear left"></div>
<div class="ear right"></div>
<div class="face">
  <div class="top"></div>
  <div class="eye"></div>
  <div class="mouth"></div>
</div>
<style>
  body {
    background: #f3ac3c;
  }
  .ear {
    position: absolute;
    width: 40;
    height: 40;
    border-radius: 50%;
    background: #1a4341;
    top: 65;
    border: 10px solid #998235;
  }
  .ear.left {
    left: 115;
  }
  .ear.right {
    right: 115;
  }
  .face {
    position: relative;
    width: 150;
    height: 150;
    border-radius: 75px 75px 60px 60px;
    background: #998235;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    overflow: hidden;
  }
  .top {
    position: absolute;
    width: 40;
    height: 40;
    background: #1a4341;
    transform: rotate(45deg);
    top: -23;
    left: 55;
  }
  .eye {
    position: absolute;
    width: 20;
    height: 20;
    background: #1a4341;
    border-radius: 50%;
    top: 60;
    left: 25;
    box-shadow: 80px 0 #1a4341;
  }
  .mouth {
    position: absolute;
    width: 100;
    height: 40;
    background: #fff;
    border-radius: 12px 12px 30px 30px;
    top: 95;
    left: 25;
  }
  .mouth::before {
    content: "";
    height: 10;
    width: 20;
    border-radius: 0 0 50px 50px;
    border: 10px solid #1a4341;
    border-top: 0;
    position: absolute;
    top: 10;
    left: 15;
    filter: drop-shadow(30px 0 #1a4341);
  }
  .mouth::after {
    content: "";
    height: 30;
    width: 10;
    background: #1a4341;
    position: absolute;
    left: 45;
    top: -10;
  }
</style>
```
