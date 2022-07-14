# Battle #16 - Aspect

## #89 - Eclipse

[Link to the problem](https://cssbattle.dev/play/90)

![target](https://cssbattle.dev/targets/90.png)

```html
<div></div>
<style>
  body {
    background: #f3ac3c;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: #1a4341;
    border-radius: 50%;
    border: 25px solid #f3ac3c;
  }
  div::before,
  div::after {
    content: "";
    width: 400px;
    height: 400px;
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
