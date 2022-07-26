# Battle #1 - Pilot Battle

## #9 - Tesseract

[Link to the problem](https://cssbattle.dev/play/9)

![target](https://cssbattle.dev/targets/9.png)

```html
<div></div>
<style>
  body {
    background: linear-gradient(#222730 25%, #4caab3 25%, #4caab3 75%, #222730 75%);
    display: grid;
    place-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    background: #4caab3;
    box-shadow: 0 0 0 50px #222730;
    transform: rotate(45deg);
    display: grid;
    place-items: center;
  }
  div::before {
    content: "";
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #393e46;
  }
</style>
```
