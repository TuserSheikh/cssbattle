# Battle #16 - Aspect

## #89 - Summit

[Link to the problem](https://cssbattle.dev/play/89)

![target](https://cssbattle.dev/targets/89.png)

```html
<div class="tri"></div>
<div class="circle"></div>
<style>
  body {
    margin: 0;
    background: #191919;
  }
  .tri {
    width: 100%;
    height: 100%;
    background: radial-gradient(circle, #191919 40%, #4f77ff 40%);
    clip-path: polygon(14.8% 100%, 50% 53%, 85.2% 100%);
  }
  .circle {
    width: 200;
    height: 200;
    border-radius: 50%;
    background: #f9e492;
    position: absolute;
    top: 50;
    left: 100;
    z-index: -1;
  }
</style>
```
