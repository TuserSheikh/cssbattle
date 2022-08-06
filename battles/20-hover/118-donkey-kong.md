# Battle #20 - Hover

## #118 - Donkey Kong

[Link to the problem](https://cssbattle.dev/play/118)

![target](https://cssbattle.dev/targets/118.png)

```html
<div class="ladder"></div>
<div class="girder top-bottom"></div>
<div class="girder mid"></div>
<style>
  body {
    background: #000;
  }
  div {
    position: absolute;
  }
  .ladder {
    height: 50px;
    width: 20px;
    background: #fff;
    top: 100px;
    left: 80px;
    box-shadow: 220px 0 #fff, 220px 50px #fff, 110px 50px #fff;
  }
  .girder {
    left: 50px;
    width: 300px;
    height: 20px;
    border-radius: 20px;
    background: #af067c;
  }
  .top-bottom {
    top: 90px;
    box-shadow: 0 100px #af067c;
  }
  .mid {
    top: 140px;
    transform: rotate(-4deg);
  }
</style>
```
