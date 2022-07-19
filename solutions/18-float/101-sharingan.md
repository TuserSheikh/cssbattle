# Battle #18 - Float

## #101 - Sharingan

[Link to the problem](https://cssbattle.dev/play/101)

![target](https://cssbattle.dev/targets/101.png)

```html
<div class="outer">
  <div class="c left"></div>
  <div class="c right"></div>
  <div class="c bottom"></div>
  <div class="mid"></div>
</div>
<style>
  body {
    background: #161616;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .outer {
    width: 190px;
    height: 190px;
    background: #a22015;
    border-radius: 50%;
    box-shadow: 0 0 0 5px;
    position: relative;
    overflow: hidden;
  }
  .c {
    position: absolute;
    width: 70px;
    height: 70px;
    background: #a22015;
    border-radius: 50%;
    box-shadow: 0 0 0 15px;
  }
  .left {
    left: -14;
    top: 17;
  }
  .right {
    right: -14;
    top: 17;
  }
  .bottom {
    left: 60;
    bottom: -25;
  }
  .mid {
    position: absolute;
    top: 70;
    left: 70;
    width: 50px;
    height: 50px;
    background: #000000;
    border-radius: 50%;
    box-shadow: 0 0 0 10px #e96a23, 0 0 0 25px #000000;
  }
</style>
```
