# Battle #7 - Backface

## #33 - Birdie

[Link to the problem](https://cssbattle.dev/play/33)

![target](https://cssbattle.dev/targets/33.png)

```html
<div class="quarter"></div>
<div class="half"></div>
<div class="circle"></div>
<style>
  body {
    background: #1a4341;
  }
  div {
    position: absolute;
  }
  .quarter {
    width: 100px;
    height: 100px;
    background: #f3ac3c;
    top: 50px;
    left: 200px;
    border-radius: 0 100px 0 0;
  }
  .half {
    width: 75px;
    height: 150px;
    background: #998235;
    top: 75px;
    left: 125px;
    border-radius: 75px 0 0 75px;
  }
  .circle {
    width: 30px;
    height: 30px;
    background: #0b2429;
    top: 105px;
    left: 155px;
    border-radius: 50%;
  }
</style>
```
