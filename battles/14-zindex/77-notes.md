# Battle #14 - ZIndex

## #77 - Notes

[Link to the problem](https://cssbattle.dev/play/77)

![target](https://cssbattle.dev/targets/77.png)

```html
<div class="steam-and-head"></div>
<div class="beam"></div>
<div class="flag"></div>
<style>
  body {
    background: #191919;
  }
  div {
    position: absolute;
    top: 90;
    background: #fe5f55;
  }
  .steam-and-head {
    left: 95;
    width: 10;
    height: 100;
    color: #fe5f55;
    filter: drop-shadow(70px 0) drop-shadow(70px 0 #a64942) drop-shadow(70px 0);
  }
  .steam-and-head::after {
    content: "";
    width: 50;
    height: 40;
    border-radius: 50%;
    background: #fe5f55;
    position: absolute;
    bottom: -20;
    left: -40;
  }
  .beam {
    width: 80;
    height: 10;
    left: 95;
  }
  .flag {
    width: 40;
    height: 10;
    background: #a64942;
    left: 235;
    box-shadow: 70px 0 #fe5f55, 70px 20px #fe5f55;
  }
</style>
```
