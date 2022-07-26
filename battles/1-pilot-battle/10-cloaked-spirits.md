# Battle #1 - Pilot Battle

## #10 - Cloaked Spirits

[Link to the problem](https://cssbattle.dev/play/10)

![target](https://cssbattle.dev/targets/10.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<style>
  body {
    background: #62306d;
  }
  div {
    position: absolute;
    width: 60px;
    height: 60px;
    border-radius: 50%;
  }
  div::after {
    content: "";
    position: absolute;
    left: -20;
    top: 50%;
    width: 100px;
    height: 200px;
    background: #f7ec7d;
    z-index: -1;
  }
  .one,
  .three {
    bottom: 50;
    left: 50;
    background: #e38f66;
    border: 20px solid #aa445f;
  }
  .two {
    bottom: 150;
    left: 150;
    background: #aa445f;
    border: 20px solid #e38f66;
  }
  .three {
    left: 250;
  }
</style>
```
