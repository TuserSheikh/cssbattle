# Battle #15 - Filter

## #82 - Diamond Cut

[Link to the problem](https://cssbattle.dev/play/82)

![target](https://cssbattle.dev/targets/82.png)

```html
<div></div>
<style>
  body {
    background: #f3ac3c;
    display: flex;
    align-items: center;
  }
  div {
    background: #1a4341;
    position: absolute;
    left: 183;
    width: 30px;
    height: 30px;
    transform: rotate(45deg);
    box-shadow: 0 0 0 35px #f3ac3c, 0 0 0 65px #998235;
  }
  div::before,
  div::after {
    content: "";
    background: #f3ac3c;
    position: absolute;
  }
  div::before {
    width: 30px;
    height: 40px;
    top: -70;
  }
  div::after {
    width: 40px;
    height: 30px;
    left: -70;
  }
</style>
```
