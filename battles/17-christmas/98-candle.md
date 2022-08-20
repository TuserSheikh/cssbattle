# Battle #17 - Chrismas

## #98 - Candle

[Link to the problem](https://cssbattle.dev/play/98)

![target](https://cssbattle.dev/targets/98.png)

```html
<div class="candle"></div>
<div class="light"></div>
<style>
  body {
    background: #14313e;
    display: flex;
    justify-content: center;
  }
  .candle {
    width: 80;
    height: 100;
    background: #ba3e46;
    position: absolute;
    top: 125;
  }
  .candle::before {
    content: "";
    width: 100%;
    height: 30;
    position: absolute;
    border-radius: 50%;
    background: #f3695a;
    top: -15;
    box-shadow: 0 100px #ba3e46;
  }
  .candle::after {
    content: "";
    width: 60;
    height: 30;
    background: #14313e;
    position: absolute;
    top: -25;
    left: 10;
    border-radius: 50%;
  }
  .light {
    width: 30;
    height: 50;
    background: #f3ac3c;
    position: absolute;
    top: 60;
    left: 200;
    border-radius: 30px 0;
  }
</style>
```
