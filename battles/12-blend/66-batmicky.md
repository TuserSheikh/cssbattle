# Battle #12 - Blend

## #66 - Batmicky

[Link to the problem](https://cssbattle.dev/play/66)

![target](https://cssbattle.dev/targets/66.png)

```html
<div class="container">
  <div class="wings"></div>
  <div class="tail"></div>
  <div class="top"></div>
  <div class="head"></div>
</div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  .container {
    width: 250;
    height: 100;
    background: #f2ad43;
    position: relative;
  }
  .wings {
    position: absolute;
    width: 100;
    height: 100;
    background: #191919;
    border-radius: 100%;
    left: -50;
    box-shadow: 250px 0 #191919;
  }
  .tail {
    position: absolute;
    top: 60;
    width: 200;
    height: 200;
    background: #191919;
    border-radius: 100%;
    left: -35;
    box-shadow: 120px 0 #191919;
  }
  .top {
    position: absolute;
    left: 85;
    width: 80;
    height: 30;
    background: #191919;
    border-radius: 0 0 10px 10px;
  }
  .head {
    position: absolute;
    left: 115;
    top: 10;
    width: 20;
    height: 20;
    background: #f2ad43;
  }
  .head::before,
  .head::after {
    width: 10;
    height: 10;
    background: #f2ad43;
    border-radius: 50%;
    content: "";
    position: absolute;
    top: -5;
  }
  .head::before {
    left: -5;
  }
  .head::after {
    right: -5;
  }
</style>
```
