# Battle #12 - Blend

## #68 - Bell

[Link to the problem](https://cssbattle.dev/play/68)

![target](https://cssbattle.dev/targets/68.png)

```html
<div></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    width: 120;
    height: 120;
    background: #e08027;
    border-radius: 60px 60px 10px 10px;
    position: absolute;
    display: flex;
    justify-content: center;
  }
  div::before,
  div::after {
    content: "";
    width: 50;
    height: 50;
    border-radius: 50%;
    position: absolute;
    z-index: -1;
  }
  div::before {
    background: #f2ad43;
    top: -25;
  }
  div::after {
    background: #824b20;
    bottom: -25;
  }
</style>
```
