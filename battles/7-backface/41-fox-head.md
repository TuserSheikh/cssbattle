# Battle #7 - Backface

## #41 - Fox Head

[Link to the problem](https://cssbattle.dev/play/41)

![target](https://cssbattle.dev/targets/41.png)

```html
<div></div>
<div></div>
<style>
  body {
    background: #293462;
  }
  div {
    position: absolute;
    top: 180px;
    left: 150px;
    width: 50px;
    height: 150px;
    border-radius: 0 40px 0 0;
    box-shadow: 0 -100px #fe5f55;
  }
  div::after {
    content: "";
    height: 30px;
    width: 30px;
    border-radius: 50%;
    background: #293462;
    position: absolute;
    left: 15px;
    top: -40px;
  }
  div:last-of-type {
    left: 200px;
    transform: scaleX(-1);
  }
</style>
```
