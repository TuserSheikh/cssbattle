# Battle #4 - Display

## #22 - Cloud

[Link to the problem](https://cssbattle.dev/play/22)

![target](https://cssbattle.dev/targets/22.png)

```html
<div></div>
<style>
  body {
    background: #f5d6b4;
  }
  div {
    background: #d86f45;
    height: 100px;
    width: 100px;
    border-radius: 50%;
    position: absolute;
    top: 85px;
    left: 180px;
    box-shadow: -80px 30px #d86f45;
  }
  div::after {
    content: "";
    width: 170px;
    height: 50px;
    border-radius: 50px;
    background: #d86f45;
    position: absolute;
    bottom: -30px;
    right: -20px;
  }
</style>
```
