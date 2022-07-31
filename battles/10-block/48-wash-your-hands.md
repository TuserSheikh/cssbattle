# Battle #10 - Block

## #48 - Wash Your Hands

[Link to the problem](https://cssbattle.dev/play/48)

![target](https://cssbattle.dev/targets/48.png)

```html
<div></div>
<style>
  body {
    background: #293462;
    display: grid;
    justify-items: center;
  }
  div {
    width: 200px;
    height: 100px;
    background: #fe5f55;
    border-radius: 20px;
    box-shadow: 0 20px #a64942;
    position: absolute;
    top: 90px;
    display: grid;
    place-items: center;
  }
  div::after {
    content: "";
    width: 140px;
    height: 40px;
    background: #a64942;
    border-radius: 40px;
  }
</style>
```
