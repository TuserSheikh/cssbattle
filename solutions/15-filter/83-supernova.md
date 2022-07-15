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
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .left,
  .right {
    position: absolute;
    width: 100px;
    height: 220px;
    background: #6592cf;
    transform: rotate(-45deg);
    border-radius: 100px;
  }
  .right {
    transform: rotate(45deg);
  }
  .mid {
    position: absolute;
    width: 120px;
    height: 120px;
    background: #243d83;
    transform: rotate(45deg);
  }
  .circle {
    position: absolute;
    width: 60px;
    height: 60px;
    background: #eeb850;
    border-radius: 50%;
  }
</style>
```
