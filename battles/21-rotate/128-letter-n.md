# Battle #20 - Rotate

## #128 - Letter N

[Link to the problem](https://cssbattle.dev/play/128)

![target](https://cssbattle.dev/targets/128.png)

```html
<div r></div>
<div m></div>
<div l></div>
<style>
  body {
    background: #998235;
  }
  div {
    position: absolute;
  }
  [r],
  [l] {
    width: 40;
    height: 230;
    background: #0b2429;
  }
  [r] {
    top: 0;
    left: 225;
  }
  [l] {
    bottom: 0;
    left: 135;
  }
  [m] {
    top: 70;
    left: 178;
    width: 43;
    height: 160;
    background: #fcbe5c;
    transform: skewX(20deg);
  }
</style>
```
