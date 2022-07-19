# Battle #18 - Float

## #103 - Super Saiyan

[Link to the problem](https://cssbattle.dev/play/103)

![target](https://cssbattle.dev/targets/103.png)

```html
<div class="hc hc1"></div>
<div class="hc hc2"></div>
<div class="head"></div>
<div class="top"></div>
<div class="hc hc3"></div>
<div class="hc hc4"></div>
<style>
  body {
    background: #161616;
  }
  .head {
    position: absolute;
    top: 150;
    left: 160;
    width: 80;
    height: 66;
    background: linear-gradient(to right, #ffffff 50%, #ffdeb9 50%);
    border-radius: 0 0 50px 50px;
  }
  .head::after {
    content: "";
    position: absolute;
    top: 36;
    left: 30;
    width: 20;
    height: 20;
    background: linear-gradient(transparent 50%, #161616 50%);
    border-radius: 50%;
  }
  .top {
    position: absolute;
    top: 96;
    left: 170;
    width: 60;
    height: 60;
    background: #ebae11;
    border-radius: 0 60px;
    transform: rotate(45deg);
  }
  .hc {
    position: absolute;
    width: 60;
    height: 30;
    background: #ebae11;
    border-radius: 0 0 60px 60px;
  }
  .hc1 {
    transform: rotate(15deg);
    top: 160;
    left: 137;
  }
  .hc2 {
    transform: rotate(-15deg);
    top: 160;
    right: 137;
  }
  .hc3 {
    transform: rotate(60deg);
    top: 134;
    left: 142;
  }
  .hc4 {
    transform: rotate(-60deg);
    top: 134;
    right: 142;
  }
</style>
```
