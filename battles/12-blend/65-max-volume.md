# Battle #12 - Blend

## #65 - Max Volume

[Link to the problem](https://cssbattle.dev/play/65)

![target](https://cssbattle.dev/targets/65.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="tri"></div>
<div class="rect"></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
  }
  .one,
  .two,
  .three {
    background: #191919;
    border-radius: 0 200px 200px 0;
    border: 10px solid #5dbcf9;
    border-left: none;
    left: 225;
  }
  .one {
    width: 90;
    height: 180;
  }
  .two {
    width: 65;
    height: 130;
  }
  .three {
    width: 40;
    height: 80;
  }
  .tri {
    border-right: 100px solid #5dbcf9;
    border-top: 100px solid transparent;
    border-bottom: 100px solid transparent;
    left: 100;
  }
  .rect {
    width: 100;
    height: 50;
    background: #5dbcf9;
    border-radius: 10px;
    left: 75;
  }
</style>
```
