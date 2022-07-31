# Battle #9 - Margin

## #46 - Mountains

[Link to the problem](https://cssbattle.dev/play/46)

![target](https://cssbattle.dev/targets/46.png)

```html
<div></div>
<style>
  body {
    background: #293462;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: #fff1c1;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
  }
  div::before,
  div::after {
    content: "";
    width: 100px;
    height: 170px;
    background: #fe5f55;
    position: absolute;
    top: 70px;
    left: 67px;
    transform: rotate(45deg);
  }
  div::after {
    top: 140px;
    left: -45px;
  }
</style>
```
