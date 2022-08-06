# Battle #19 - Spacing

## #115 - Droplet

[Link to the problem](https://cssbattle.dev/play/115)

![target](https://cssbattle.dev/targets/115.png)

```html
<div class="top"></div>
<div class="bottom"></div>
<div class="circle"></div>
<style>
  body {
    margin: 0;
    background: linear-gradient(#c36271 50%, #f2e09f 50%);
  }
  .top,
  .bottom {
    position: absolute;
    width: 95%;
    height: 50%;
  }
  .top {
    background: #f2e09f;
    border-radius: 0 0 100px 0;
  }
  .bottom {
    bottom: 0;
    right: 0;
    background: #c36271;
    border-radius: 100px 0 0 0;
  }
  .circle {
    position: absolute;
    top: 100px;
    left: 150px;
    height: 100px;
    width: 100px;
    background: linear-gradient(#c36271 50%, #f2e09f 50%);
    border-radius: 50%;
  }
</style>
```
