# Battle #2 - Visibility

## #17 - Fidget Spinner

[Link to the problem](https://cssbattle.dev/play/17)

![target](https://cssbattle.dev/targets/17.png)

```html
<main>
  <div class="left"></div>
  <div class="right"></div>
  <div class="top"></div>
  <div class="bottom"></div>
</main>
<style>
  body {
    background: #09042a;
    display: grid;
    place-items: center;
  }
  main {
    width: 80px;
    height: 80px;
    background: #e78481;
    border-radius: 50%;
    position: relative;
  }
  div {
    width: 60px;
    height: 60px;
    position: absolute;
    border-radius: 50%;
  }
  .left {
    left: -60px;
    background: #09042a;
    border: 10px solid #e78481;
  }
  .right {
    right: -60px;
    background: #09042a;
    border: 10px solid #e78481;
  }
  .top {
    top: -53px;
    background: #f5bb9c;
    border: 10px solid #09042a;
  }
  .bottom {
    bottom: -53px;
    background: #f5bb9c;
    border: 10px solid #09042a;
  }
</style>
```
