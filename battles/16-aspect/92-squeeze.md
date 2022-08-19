# Battle #16 - Aspect

## #92 - Squeeze

[Link to the problem](https://cssbattle.dev/play/92)

![target](https://cssbattle.dev/targets/92.png)

```html
<div></div>
<style>
  body {
    background: linear-gradient(#6592cf 43%, #243d83 43% 57%, #6592cf 57%);
    display: grid;
    place-items: center;
  }
  div {
    width: 200;
    height: 200;
    background: #243d83;
    border-radius: 50%;
    color: #243d83;
    box-shadow: 226px 0, -226px 0;
  }
  div::after {
    content: "";
    height: 32;
    width: 32;
    border-radius: 50%;
    background: #6592cf;
    position: absolute;
    left: 71;
    top: 108;
    color: #6592cf;
    box-shadow: 0 52px, 226px 0, 226px 52px;
  }
</style>
```
