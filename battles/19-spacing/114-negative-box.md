# Battle #19 - Spacing

## #114 - Negative Box

[Link to the problem](https://cssbattle.dev/play/114)

![target](https://cssbattle.dev/targets/114.png)

```html
<div class="rect"></div>
<div class="tri"></div>
<style>
  * {
    background: #172d2c;
  }
  .tri {
    position: absolute;
    top: 20;
    left: 200;
    border-left: 180px solid #e9af53;
    border-top: 65px solid transparent;
    border-bottom: 65px solid transparent;
  }
  .rect {
    width: 180px;
    height: 130px;
    position: absolute;
    background: #e9af53;
    top: 117;
    left: 20;
    transform: skewY(20deg);
  }
</style>
```
