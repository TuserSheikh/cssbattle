# Battle #15 - Filter

## #83 - Supernova

[Link to the problem](https://cssbattle.dev/play/83)

![target](https://cssbattle.dev/targets/83.png)

```html
<div class="left"></div>
<div class="right"></div>
<div class="mid"></div>
<div class="circle"></div>
<style>
  body {
    background: #243d83;
    display: grid;
    place-items: center;
  }
  .left,
  .right {
    position: absolute;
    width: 100;
    height: 220;
    background: #6592cf;
    transform: rotate(-45deg);
    border-radius: 100px;
  }
  .right {
    transform: rotate(45deg);
  }
  .mid {
    position: absolute;
    width: 120;
    height: 120;
    background: #243d83;
    transform: rotate(45deg);
  }
  .circle {
    position: absolute;
    width: 60;
    height: 60;
    background: #eeb850;
    border-radius: 50%;
  }
</style>
```
