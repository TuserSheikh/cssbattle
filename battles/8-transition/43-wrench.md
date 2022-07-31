# Battle #8 - Transition

## #43 - Wrench

[Link to the problem](https://cssbattle.dev/play/43)

![target](https://cssbattle.dev/targets/43.png)

```html
<div></div>
<style>
  body {
    background: #6592cf;
    display: grid;
    place-items: center;
  }
  div {
    width: 110px;
    height: 245px;
    position: relative;
    overflow: hidden;
  }
  div::before,
  div::after {
    content: "";
    height: 182px;
    width: 80px;
    background: #6592cf;
    position: absolute;
    left: -40px;
    top: 32px;
    border-radius: 40px;
    box-shadow: 0 0 0 30px #243d83;
  }
  div::after {
    left: 70;
  }
</style>
```
