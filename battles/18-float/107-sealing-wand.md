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
  body {
    background: #161616;
  }
  div {
    position: absolute;
  }
  .bottom {
    top: 200px;
    left: 190px;
    width: 20px;
    height: 110px;
    background: #e96a23;
  }
  .right {
    top: 129px;
    left: 200px;
    width: 80px;
    height: 40px;
    background: #e96a23;
    border-radius: 0 40px 5px 0;
  }
  .mid {
    top: 120px;
    left: 170px;
    width: 60px;
    height: 60px;
    background: #a22015;
    border-radius: 50%;
  }
  .mid-down {
    top: 153px;
    left: 185px;
    width: 30px;
    height: 50px;
    background: #a22015;
    border-radius: 0 0 10px 10px;
  }
  .left {
    top: 132px;
    left: 130px;
    width: 55px;
    height: 12px;
    background: #fff;
    border-radius: 0 0 0 40px;
    box-shadow: 15px 12px #fff, 30px 24px #fff;
  }
  .top {
    top: 135px;
    left: 185px;
    width: 20px;
    height: 20px;
    background: #161616;
    border-radius: 50%;
    border: 5px solid #a22015;
    box-shadow: 0 0 0 10px #fff;
  }
</style>
```
