# Battle #10 - Block

## #47 - Corona Virus

[Link to the problem](https://cssbattle.dev/play/47)

![target](https://cssbattle.dev/targets/47.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="circle">
  <div class="big"></div>
  <div class="mid"></div>
  <div class="small"></div>
</div>
<style>
  body {
    background: #1a4341;
    display: grid;
    place-items: center;
  }
  .one,
  .two,
  .three {
    width: 10px;
    height: 180px;
    background: #f3ac3c;
    position: absolute;
    border-radius: 10px;
    top: 50px;
  }
  .two {
    top: 55px;
    left: 204px;
    transform: rotate(60deg);
  }
  .three {
    top: 65px;
    left: 204px;
    transform: rotate(1200deg);
  }
  .circle {
    width: 100px;
    height: 100px;
    background: #f3ac3c;
    border-radius: 50%;
    position: relative;
  }
  .big,
  .mid,
  .small {
    background: #998235;
    border-radius: 50%;
    position: absolute;
    width: 30px;
    height: 30px;
    top: 20px;
    left: 20px;
  }
  .mid {
    width: 20px;
    height: 20px;
    top: 65px;
    left: 40px;
  }
  .small {
    width: 10px;
    height: 10px;
    top: 20px;
    left: 70px;
  }
</style>
```
