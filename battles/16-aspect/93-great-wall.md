# Battle #16 - Aspect

## #93 - Great Wall

[Link to the problem](https://cssbattle.dev/play/93)

![target](https://cssbattle.dev/targets/93.png)

```html
<main>
  <div class="circle"></div>
  <div class="bar-1"></div>
  <div class="bar-2"></div>
  <div class="bar-3"></div>
</main>
<style>
  body {
    background: #4f77ff;
    display: grid;
    place-items: center;
  }
  main {
    width: 200;
    height: 200;
    background: #191919;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
  }
  .circle {
    width: 40;
    height: 40;
    background: #f9e492;
    border-radius: 50%;
    position: absolute;
    top: 40;
    left: 40;
  }
  .bar-1,
  .bar-2,
  .bar-3 {
    position: absolute;
    height: 16;
    box-shadow: 0 10px #191919, 0 26px #f9e492, 0 36px #191919, 0 52px #f9e492, 0 65px #191919;
  }
  .bar-1 {
    width: 100%;
    background: #f9e492;
    top: 122;
  }
  .bar-2 {
    width: 20;
    background: #d6b73f;
    top: 115;
    left: 100;
    transform: skewY(-33deg);
    box-shadow: 0 10px #191919, 0 26px #d6b73f, 0 36px #191919, 0 52px #d6b73f, 0 65px #191919;
  }
  .bar-3 {
    width: 100;
    background: #f9e492;
    top: 109;
    left: 120;
  }
</style>
```
