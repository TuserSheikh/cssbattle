# Battle #11 - Overflow

## #60 - Evil Triangles

[Link to the problem](https://cssbattle.dev/play/60)

![target](https://cssbattle.dev/targets/60.png)

```html
<div class="container">
  <div class="top">
    <div class="tri-blue"></div>
  </div>
  <div class="mid">
    <div class="tri-black"></div>
  </div>
  <div class="bottom">
    <div class="tri-blue"></div>
  </div>
</div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  .container {
    width: 200;
    height: 150;
    position: relative;
  }
  .top,
  .bottom,
  .mid {
    height: 50;
    background: #191919;
    display: flex;
  }
  .mid {
    background: #4f77ff;
  }
  .tri-blue,
  .tri-black {
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
  }
  .tri-blue {
    border-top: 50px solid #4f77ff;
    filter: drop-shadow(100px 0 #4f77ff);
  }
  .tri-black {
    border-top: 50px solid #191919;
    filter: drop-shadow(100px 0 #191919);
  }
</style>
```
