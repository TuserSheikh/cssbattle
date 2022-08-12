# Battle #11 - Overflow

## #60 - Evil Triangles

[Link to the problem](https://cssbattle.dev/play/60)

![target](https://cssbattle.dev/targets/60.png)

```html
<main>
  <div class="left"></div>
  <div class="right"></div>
</main>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  main {
    width: 200;
    height: 150;
    background: #4f77ff;
    position: relative;
  }
  div {
    background: #191919;
    width: 50;
    height: 50;
    position: absolute;
    top: 25;
  }
  .left {
    transform: skewY(45deg);
    box-shadow: 0 100px #191919, 100px -100px #191919, 100px 0 #191919;
  }
  .right {
    transform: skewY(-45deg);
    left: 50;
    box-shadow: 0 100px #191919, 100px 100px #191919, 100px 200px #191919;
  }
</style>
```
