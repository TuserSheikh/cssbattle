# Battle #20 - Hover

## #121 - Duck Hunt

[Link to the problem](https://cssbattle.dev/play/121)

![target](https://cssbattle.dev/targets/121.png)

```html
<div></div>
<style>
  body {
    background: linear-gradient(#1e92ff 180px, #69d10a 180px 220px, #6f6100 220px);
  }
  div {
    position: absolute;
    width: 20;
    height: 80;
    background: #441a0a;
    top: 100;
    left: 50;
  }
  div::after {
    content: "";
    width: 40;
    height: 40;
    background: #69d10a;
    color: #69d10a;
    border-radius: 50%;
    position: absolute;
    top: -20;
    left: -10;
    box-shadow: 0 -20px, -20px 0, 20px 0, 270px 50px, 270px 70px;
  }
</style>
```
