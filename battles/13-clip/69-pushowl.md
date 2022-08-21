# Battle #13 - Clip

## #69 - PushOwl (99.9%)

[Link to the problem](https://cssbattle.dev/play/69)

![target](https://cssbattle.dev/targets/69.png)

```html
<div class="left"></div>
<div class="right"></div>
<div class="bottom"></div>
<style>
  body {
    background: #191919;
  }
  .left,
  .right {
    width: 114;
    height: 114;
    background: #e08027;
    position: absolute;
    top: 77;
    display: grid;
    place-items: center;
  }
  .left {
    left: 89;
    border-radius: 0 60px 60px 60px;
  }
  .right {
    left: 197;
    border-radius: 60px 0 60px 60px;
    box-shadow: 0 0 0 10px #191919;
  }
  .left::before,
  .right::before {
    content: "";
    width: 90;
    height: 90;
    background: #191919;
    position: absolute;
    border-radius: 50%;
  }
  .left::after,
  .right::after {
    content: "";
    width: 30;
    height: 15;
    position: absolute;
    border-radius: 50px 50px 0 0;
    border: 9px solid #e08027;
    border-bottom: 0;
    top: 48;
    box-sizing: border-box;
  }
  .bottom {
    width: 50;
    height: 50;
    background: #e08027;
    position: absolute;
    top: 162;
    left: 175;
    transform: rotate(45deg);
    z-index: -1;
  }
</style>
```
