# Battle #4 - Display

## #25 - Blossom

[Link to the problem](https://cssbattle.dev/play/25)

![target](https://cssbattle.dev/targets/25.png)

```html
<div class="green up"></div>
<div class="green down"></div>
<div class="yellow up"></div>
<div class="yellow down"></div>
<style>
  body {
    background: #998235;
  }
  div {
    position: absolute;
  }
  .green {
    height: 100px;
    width: 80px;
    background: #1a4341;
  }
  .green.up {
    border-radius: 0 50px;
    top: 60px;
    left: 110px;
  }
  .green.down {
    border-radius: 50px 0;
    top: 140px;
    left: 210px;
  }
  .yellow {
    height: 60px;
    width: 80px;
    background: #f3ac3c;
  }
  .yellow.up {
    top: 60px;
    left: 210px;
    border-radius: 50px 0;
  }
  .yellow.down {
    top: 180px;
    left: 110px;
    border-radius: 0 50px;
  }
</style>
```
