# Battle #17 - Chrismas

## #98 - Candle

[Link to the problem](https://cssbattle.dev/play/98)

![target](https://cssbattle.dev/targets/98.png)

```html
<div class="light"></div>
<div class="candle"></div>
<style>
  body {
    background: #14313e;
    display: flex;
    justify-content: center;
  }
  .candle {
    width: 80px;
    height: 100px;
    background: #ba3e46;
    position: absolute;
    top: 125;
  }
  .candle::before,
  .candle::after {
    content: "";
    width: 100%;
    height: 30px;
    position: absolute;
    border-radius: 50%;
  }
  .candle::before {
    background: #f3695a;
    top: -15;
  }
  .candle::after {
    bottom: -15;
    background: #ba3e46;
  }
  .light {
    width: 60px;
    height: 30px;
    background: #14313e;
    position: absolute;
    top: 100;
    border-radius: 50%;
    z-index: 1;
  }
  .light::after {
    content: "";
    width: 30px;
    height: 50px;
    background: #f3ac3c;
    position: absolute;
    top: -40;
    left: 30;
    border-radius: 30px 0;
  }
</style>
```
