# Battle #10 - Block

## #49 - Stay at Home

[Link to the problem](https://cssbattle.dev/play/49)

![target](https://cssbattle.dev/targets/49.png)

```html
<div class="house">
  <div class="top"></div>
  <div class="bottom"></div>
</div>
<style>
  body {
    background: #6592cf;
    display: grid;
    place-items: center;
  }
  .top {
    border-bottom: 100px solid #243d83;
    border-left: 100px solid #6592cf;
    border-right: 100px solid #6592cf;
  }
  .bottom {
    width: 150px;
    height: 100px;
    background: #243d83;
    position: relative;
    display: grid;
    justify-items: center;
    margin: auto;
    border-radius: 0 0 10px 10px;
  }
  .bottom::before,
  .bottom::after {
    content: "";
    background: #eeb850;
    position: absolute;
  }
  .bottom::before {
    width: 100px;
    height: 10px;
    border-radius: 10px;
    top: -5px;
  }
  .bottom::after {
    width: 50px;
    height: 50px;
    bottom: 0;
    border-radius: 10px 10px 0 0;
  }
</style>
```
