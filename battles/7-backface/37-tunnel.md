# Battle #7 - Backface

## #37 - Tunnel

[Link to the problem](https://cssbattle.dev/play/37)

![target](https://cssbattle.dev/targets/37.png)

```html
<div></div>
<style>
  body {
    background: #6592cf;
    display: grid;
    place-items: center;
  }
  div {
    width: 250px;
    height: 250px;
    background: #243d83;
    position: relative;
  }
  div::before {
    content: "";
    position: absolute;
    top: 50px;
    left: 50px;
    width: 150px;
    height: 150px;
    background: #6592cf;
    transform: rotate(15deg);
  }
  div::after {
    content: "";
    position: absolute;
    top: 88px;
    left: 88px;
    width: 75px;
    height: 75px;
    background: #243d83;
    transform: rotate(30deg);
  }
</style>
```
