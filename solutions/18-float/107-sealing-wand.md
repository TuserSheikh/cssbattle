# Battle #18 - Float

## #107 - Sealing Wand

[Link to the problem](https://cssbattle.dev/play/107)

![target](https://cssbattle.dev/targets/107.png)

```html
<div class="bottom"></div>
<div class="right"></div>
<div class="mid"></div>
<div class="mid-down"></div>
<div class="left"></div>
<div class="top"></div>
<style>
  * {
    background: #161616;
  }
  .bottom {
    position: absolute;
    top: 200;
    left: 190;
    width: 20px;
    height: 110px;
    background: #e96a23;
  }
  .right {
    position: absolute;
    top: 129;
    left: 200;
    width: 80px;
    height: 40px;
    background: #e96a23;
    border-radius: 0 40px 5px 0;
  }
  .mid {
    position: absolute;
    top: 120;
    left: 170;
    width: 60px;
    height: 60px;
    background: #a22015;
    border-radius: 50%;
  }
  .mid-down {
    position: absolute;
    top: 153;
    left: 185;
    width: 30px;
    height: 50px;
    background: #a22015;
    border-radius: 0 0 10px 10px;
  }
  .left {
    position: absolute;
    top: 132;
    left: 130;
    width: 55px;
    height: 12px;
    background: #ffffff;
    border-radius: 0 0 0 40px;
    box-shadow: 15px 12px #ffffff, 30px 24px #ffffff;
  }
  .top {
    position: absolute;
    top: 135;
    left: 185;
    width: 20px;
    height: 20px;
    background: #161616;
    border-radius: 50%;
    border: 5px solid #a22015;
    box-shadow: 0 0 0 10px #ffffff;
  }
</style>
```
