# Battle #16 - Aspect

## #96 - Mandala

[Link to the problem](https://cssbattle.dev/play/96)

![target](https://cssbattle.dev/targets/96.png)

```html
<div class="circle">
  <div class="c1"></div>
  <div class="c2"></div>
  <div class="c3"></div>
  <div class="c4"></div>
</div>
<style>
  body {
    background: #243d83;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 200px;
    height: 200px;
    background: #6592cf;
    border-radius: 50%;
    position: relative;
  }
  .c1,
  .c2,
  .c3,
  .c4 {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    position: absolute;
    box-shadow: 0 0 0 20px #243d83;
  }
  .c1 {
    left: -40;
    top: 35;
  }
  .c2 {
    right: -40;
    top: 35;
  }
  .c3 {
    top: -40;
    left: 35;
  }
  .c4 {
    bottom: -40;
    left: 35;
  }
</style>
```
