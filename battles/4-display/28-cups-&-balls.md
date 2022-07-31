# Battle #4 - Display

## #28 - Cups & Balls

[Link to the problem](https://cssbattle.dev/play/28)

![target](https://cssbattle.dev/targets/28.png)

```html
<div class="ball"></div>
<div class="cup-up"></div>
<div class="cup-down"></div>
<style>
  body {
    background: #1a4341;
  }
  div {
    width: 50px;
    height: 50px;
    position: absolute;
  }
  .ball {
    background: #998235;
    border-radius: 50%;
    top: 90px;
    left: 70px;
    box-shadow: 210px 0 #f3ac3c, 70px 70px #998235, 140px 70px #f3ac3c;
  }
  .cup-up {
    background: #f3ac3c;
    border-radius: 50% 50% 0 0;
    top: 90px;
    left: 140px;
    box-shadow: 70px 0 #998235;
  }
  .cup-down {
    background: #f3ac3c;
    border-radius: 0 0 50% 50%;
    top: 160px;
    left: 70px;
    box-shadow: 210px 0 #998235;
  }
</style>
```
