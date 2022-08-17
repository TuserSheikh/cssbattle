# Battle #12 - Blend

## #64 - Door Knob

[Link to the problem](https://cssbattle.dev/play/64)

![target](https://cssbattle.dev/targets/64.png)

```html
<div class="circle"></div>
<div class="half-circle"></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  .circle {
    position: absolute;
    width: 100;
    height: 100;
    background: #e08027;
    border-radius: 50%;
    box-shadow: 0 0 0 30px #824b20;
  }
  .half-circle {
    position: absolute;
    top: 150;
    width: 80;
    height: 40;
    border-radius: 0 0 60px 60px;
    border: 20px solid #fff58f;
    border-top: none;
  }
  .half-circle::before,
  .half-circle::after {
    width: 20;
    height: 20;
    background: #fff58f;
    border-radius: 50%;
    top: -10;
    content: "";
    position: absolute;
  }
  .half-circle::before {
    left: -20;
  }
  .half-circle::after {
    right: -20;
  }
</style>
```
