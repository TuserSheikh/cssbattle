# Battle #16 - Aspect

## #96 - Mandala (99.9%)

[Link to the problem](https://cssbattle.dev/play/96)

![target](https://cssbattle.dev/targets/96.png)

```html
<div class="left-right"></div>
<div class="top-bottom"></div>
<style>
  body {
    background: radial-gradient(circle, #6592cf 40%, #243d83 40%);
  }
  div {
    width: 130;
    height: 130;
    border: 20px solid #243d83;
    border-radius: 50%;
    position: absolute;
    color: #243d83;
  }
  .left-right {
    top: 65;
    left: 40;
    filter: drop-shadow(150px 0);
  }
  .top-bottom {
    top: -10;
    left: 115;
    filter: drop-shadow(0 150px);
  }
</style>
```
