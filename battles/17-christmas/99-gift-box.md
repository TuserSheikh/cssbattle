# Battle #17 - Chrismas

## #99 - Gift Box

[Link to the problem](https://cssbattle.dev/play/99)

![target](https://cssbattle.dev/targets/99.png)

```html
<div class="top-left"></div>
<div class="top-right"></div>
<div class="box"></div>
<style>
  body {
    background: #ac474b;
    display: flex;
    justify-content: center;
  }
  .top-left,
  .top-right {
    width: 20px;
    height: 20px;
    position: absolute;
    border: 10px solid #ffffff;
    top: 50;
  }
  .top-left {
    border-radius: 20px 20px 0;
    left: 165;
  }
  .top-right {
    border-radius: 20px 20px 20px 0;
    right: 165;
  }
  .box {
    width: 140px;
    height: 140px;
    background: #ffffff;
    position: absolute;
    top: 110;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .box::before,
  .box::after {
    content: "";
    width: 20px;
    height: 100%;
    background: #ac474b;
    position: absolute;
  }
  .box::after {
    transform: rotate(90deg);
  }
</style>
```
