# Battle #19 - Spacing

## #115 - Droplet

[Link to the problem](https://cssbattle.dev/play/115)

![result](https://cssbattle.dev/targets/115.png)

```html
<div class="top"></div>
<div class="bottom"></div>
<div class="circle"></div>
<style>
  body {
    margin: 0;
  }
  .top {
    height: 50%;
    background: #c36271;
  }
  .bottom {
    height: 50%;
    background: #f2e09f;
  }
  .top::after,
  .bottom::after {
    content: "";
    position: absolute;
    width: 95%;
    height: 50%;
  }
  .top::after {
    background: #f2e09f;
    border-radius: 0 0 100px 0;
  }
  .bottom::after {
    bottom: 0;
    right: 0;
    background: #c36271;
    border-radius: 100px 0 0 0;
  }
  .circle {
    position: absolute;
    top: 100;
    left: 150;
    height: 100px;
    width: 100px;
    background: linear-gradient(#c36271 50%, #f2e09f 50%);
    border-radius: 50%;
  }
</style>
```
