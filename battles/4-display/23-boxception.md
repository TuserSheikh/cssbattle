# Battle #4 - Display

## #23 - Boxceptions

[Link to the problem](https://cssbattle.dev/play/23)

![target](https://cssbattle.dev/targets/23.png)

```html
<div></div>
<style>
  body {
    background: #f3ac3c;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: conic-gradient(from -90deg, #1a4341 270deg, #998235 270deg);
    position: relative;
  }
  div::after {
    content: "";
    position: absolute;
    left: 50;
    bottom: 0;
    width: 50px;
    height: 50px;
    background: #f3ac3c;
  }
</style>
```
