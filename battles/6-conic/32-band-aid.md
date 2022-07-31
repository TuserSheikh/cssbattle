# Battle #6 - Conic

## #32 - Band-aid

[Link to the problem](https://cssbattle.dev/play/32)

![target](https://cssbattle.dev/targets/32.png)

```html
<div></div>
<div></div>
<style>
  body {
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    height: 200px;
    width: 50px;
    background: #f3ac3c;
    transform: rotate(-45deg);
  }
  div:last-of-type {
    transform: rotate(45deg);
    background: linear-gradient(#a3a368 75px, #fbe18c 75px, #fbe18c 125px, #a3a368 125px);
  }
</style>
```
