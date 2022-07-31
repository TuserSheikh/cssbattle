# Battle #7 - Backface

## #35 - Ice Cream

[Link to the problem](https://cssbattle.dev/play/35)

![target](https://cssbattle.dev/targets/35.png)

```html
<div></div>
<style>
  body {
    background: #293462;
  }
  div {
    width: 100px;
    height: 150px;
    background: #fff1c1;
    position: absolute;
    top: 50px;
    left: 150px;
    border-radius: 50px 50px 20px 20px;
  }
  div::after {
    content: "";
    position: absolute;
    bottom: -50px;
    left: 35px;
    width: 30px;
    height: 50px;
    background: linear-gradient(#a64942 10px, #fe5f55 10px);
    border-radius: 0 0 10px 10px;
  }
</style>
```
