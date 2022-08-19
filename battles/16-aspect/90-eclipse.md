# Battle #16 - Aspect

## #90 - Eclipse

[Link to the problem](https://cssbattle.dev/play/90)

![target](https://cssbattle.dev/targets/90.png)

```html
<div></div>
<style>
  body {
    background: #f3ac3c;
    display: grid;
    place-items: center;
  }
  div {
    width: 200;
    height: 200;
    background: #1a4341;
    border-radius: 50%;
    border: 25px solid #f3ac3c;
  }
  div::before,
  div::after {
    content: "";
    width: 400;
    height: 400;
    background: #998235;
    border-radius: 50%;
    position: absolute;
    left: 0;
  }
  div::before {
    top: -250;
    z-index: -1;
  }
  div::after {
    bottom: -250;
  }
</style>
```
