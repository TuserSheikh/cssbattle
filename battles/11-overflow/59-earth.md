# Battle #11 - Overflow

## #59 - Earth

[Link to the problem](https://cssbattle.dev/play/59)

![target](https://cssbattle.dev/targets/59.png)

```html
<div></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    background: #dd6b4d;
    border-radius: 50%;
    background: repeating-linear-gradient(#4f77ff, #4f77ff 30px, #191919 30px, #191919 40px, #4f77ff 40px);
  }
  div::before {
    content: "";
    width: 10px;
    height: 100%;
    background: #191919;
    position: absolute;
    left: 195px;
  }
  div::after {
    content: "";
    width: 106px;
    height: 106px;
    position: absolute;
    left: 137px;
    top: 87px;
    transform: rotate(45deg);
    border-radius: 0 106px 0 106px;
    border: 10px solid #191919;
  }
</style>
```
