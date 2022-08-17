# Battle #12 - Blend

## #61 - ImprovMX

[Link to the problem](https://cssbattle.dev/play/61)

![target](https://cssbattle.dev/targets/61.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="four"></div>
<div class="five"></div>
<div class="six"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
  }
  .one {
    width: 30px;
    height: 20px;
    background: #191919;
    position: absolute;
    border: 10px solid #5dbcf9;
    top: 66;
  }
  .two {
    width: 80px;
    height: 50px;
    background: #191919;
    position: absolute;
    border: 10px solid #5dbcf9;
    top: 96;
  }
  .three {
    width: 0;
    height: 0;
    position: absolute;
    top: 125;
    left: 122;
    border-right: 80px solid #5dbcf9;
    border-top: 46px solid transparent;
    border-bottom: 140px solid transparent;
  }
  .three::after {
    content: "";
    width: 0;
    height: 0;
    position: absolute;
    top: -31;
    left: 14;
    border-right: 59px solid #191919;
    border-top: 34px solid transparent;
    border-bottom: 100px solid transparent;
  }
  .four {
    width: 0;
    height: 0;
    position: absolute;
    top: 125;
    right: 122;
    border-right: 80px solid #5dbcf9;
    border-top: 46px solid transparent;
    border-bottom: 140px solid transparent;
    transform: scaleX(-1);
  }
  .four::after {
    content: "";
    width: 0;
    height: 0;
    position: absolute;
    top: -31;
    left: 14;
    border-right: 59px solid #191919;
    border-top: 34px solid transparent;
    border-bottom: 100px solid transparent;
  }
  .five {
    width: 200px;
    height: 10px;
    background: #5dbcf9;
    position: absolute;
    top: 194;
    border-top: 10px solid #191919;
    border-bottom: 10px solid #191919;
  }
  .six {
    width: 110px;
    height: 10px;
    background: #5dbcf9;
    position: absolute;
    top: 224;
    border-bottom: 70px solid #191919;
  }
</style>
```
