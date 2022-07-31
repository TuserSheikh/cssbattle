# Battle #8 - Transition

## #44 - Stripes

[Link to the problem](https://cssbattle.dev/play/44)

![target](https://cssbattle.dev/targets/44.png)

```html
<div></div>
<style>
  body {
    background: #1a4341;
    display: grid;
    place-items: center;
  }
  div {
    width: 160px;
    height: 180px;
    background: repeating-linear-gradient(#f3ac3c, #f3ac3c 20px, #1a4341 20px, #1a4341 40px);
  }
  div::before,
  div::after {
    content: "";
    width: 300px;
    height: 300px;
    background: #1a4341;
    border-radius: 100%;
    position: absolute;
    left: -150px;
    top: 0;
  }
  div::after {
    left: 250px;
  }
</style>
```
