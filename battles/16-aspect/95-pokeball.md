# Battle #16 - Aspect

## #95 - Pokeball

[Link to the problem](https://cssbattle.dev/play/95)

![target](https://cssbattle.dev/targets/95.png)

```html
<div></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #6cb3a9;
  }
  div {
    width: 200px;
    height: 200px;
    background: linear-gradient(#d25b70 45%, #6cb3a9 45%, #6cb3a9 55%, #ffffff 55%);
    border-radius: 50%;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div::before {
    content: "";
    position: absolute;
    width: 180px;
    height: 20px;
    background: #781728;
  }
  div::after {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #f6df96;
    border-radius: 50%;
    border: 10px solid #781728;
  }
</style>
```
