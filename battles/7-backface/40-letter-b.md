# Battle #7 - Backface

## #40 - Letter B

[Link to the problem](https://cssbattle.dev/play/40)

![target](https://cssbattle.dev/targets/40.png)

```html
<div></div>
<style>
  body {
    background: #6592cf;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: #dd6b4d;
    border-radius: 0 50% 50%;
    background: #243d83;
    display: grid;
    place-items: center;
  }
  div::before {
    content: "";
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: #6592cf;
  }
  div::after {
    content: "";
    position: absolute;
    top: 50px;
    left: 150px;
    width: 50px;
    height: 100px;
    background: #6592cf;
  }
</style>
```
