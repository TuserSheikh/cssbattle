# Battle #16 - Aspect

## #95 - Pokeball

[Link to the problem](https://cssbattle.dev/play/95)

![target](https://cssbattle.dev/targets/95.png)

```html
<div></div>
<style>
  body {
    display: grid;
    place-items: center;
    background: #6cb3a9;
  }
  div {
    width: 200;
    height: 200;
    background: linear-gradient(#d25b70 45%, #6cb3a9 45% 55%, #fff 55%);
    border-radius: 50%;
    position: relative;
    display: grid;
    place-items: center;
  }
  div::before {
    content: "";
    width: 180;
    height: 20;
    background: #781728;
  }
  div::after {
    content: "";
    position: absolute;
    width: 50;
    height: 50;
    background: #f6df96;
    border-radius: 50%;
    border: 10px solid #781728;
  }
</style>
```
