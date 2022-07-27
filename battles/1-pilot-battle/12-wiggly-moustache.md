# Battle #1 - Pilot Battle

## #12 - Wiggly Moustache

[Link to the problem](https://cssbattle.dev/play/12)

![target](https://cssbattle.dev/targets/12.png)

```html
<div class="left"></div>
<div class="middle"></div>
<div class="right"></div>
<style>
  body {
    background: #f5d6b4;
  }
  div {
    height: 30px;
    width: 60px;
    border-radius: 0 0 60px 60px;
    border: 20px solid #d86f45;
    border-top: 0;
    position: absolute;
  }
  div::after {
    content: "";
    width: 20px;
    height: 20px;
    background: #d86f45;
    position: absolute;
    left: -20px;
    top: -10px;
    border-radius: 10px;
    box-shadow: 80px 0 #d86f45;
  }
  .left {
    top: 150px;
    left: 70px;
  }
  .middle {
    transform: rotate(180deg);
    top: 100px;
    left: 150px;
  }
  .right {
    top: 150px;
    right: 70px;
  }
</style>
```
