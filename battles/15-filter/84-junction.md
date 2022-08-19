# Battle #15 - Filter

## #84 - Junction

[Link to the problem](https://cssbattle.dev/play/84)

![target](https://cssbattle.dev/targets/84.png)

```html
<div class="top"></div>
<div class="right"></div>
<div class="bottom"></div>
<div class="left"></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    width: 40;
    height: 200;
    border-radius: 20px;
    background: #fe5f55;
  }
  .top {
    top: -70;
  }
  .bottom {
    bottom: -70;
  }
  .right,
  .left {
    background: #a64942;
    transform: rotate(90deg);
  }
  .right {
    right: 60;
  }
  .left {
    left: 60;
  }
</style>
```
