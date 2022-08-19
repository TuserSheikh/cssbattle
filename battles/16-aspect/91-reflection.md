# Battle #16 - Aspect

## #91 - Reflection

[Link to the problem](https://cssbattle.dev/play/91)

![target](https://cssbattle.dev/targets/91.png)

```html
<div class="circle"></div>
<div class="reflect"></div>
<style>
  body {
    background: linear-gradient(#d25b70 50%, #6cb3a9 50%);
  }
  div {
    position: absolute;
  }
  .circle {
    width: 200;
    height: 200;
    background: #f6df96;
    border-radius: 50%;
    top: 50;
    left: 100;
  }
  .reflect {
    top: 142;
    height: 50%;
    background: repeating-linear-gradient(#6cb3a9 0 15px, transparent 15px 25px);
    position: relative;
  }
</style>
```
