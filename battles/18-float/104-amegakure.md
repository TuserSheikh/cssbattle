# Battle #18 - Float

## #104 - Amegakure

[Link to the problem](https://cssbattle.dev/play/104)

![target](https://cssbattle.dev/targets/104.png)

```html
<div class="outer">
  <div class="inner">
    <div class="dot"></div>
    <div class="bar"></div>
  </div>
</div>
<style>
  body {
    background: #000;
    display: grid;
    place-items: center;
  }
  .outer {
    width: 240px;
    height: 120px;
    background: #37385a;
    border-radius: 20px;
    display: grid;
    place-items: center;
  }
  .inner {
    width: 200px;
    height: 80px;
    background: linear-gradient(-75deg, #9897ae 82px, #c0c3db 82px 132px, #9897ae 132px);
    border-radius: 10px;
    position: relative;
  }
  .dot {
    width: 10px;
    height: 10px;
    background: #000;
    border-radius: 50%;
    margin: 15px;
    box-shadow: 160px 0, 0 20px, 160px 20px, 0 40px, 160px 40px;
  }
  .bar {
    width: 10px;
    height: 50px;
    border-radius: 50px;
    background: #000;
    position: absolute;
    top: 15px;
    left: 65px;
    box-shadow: 20px 0, 40px 0, 60px 0;
  }
</style>
```
