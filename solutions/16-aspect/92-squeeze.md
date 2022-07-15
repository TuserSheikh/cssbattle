# Battle #16 - Aspect

## #92 - Squeeze

[Link to the problem](https://cssbattle.dev/play/92)

![target](https://cssbattle.dev/targets/92.png)

```html
<div class="c1"></div>
<div class="c2"></div>
<div class="c3"></div>
<style>
  body {
    margin: 0;
    background: linear-gradient(#6592CF 43%, #243D83 43%, #243D83 57%, #6592CF 57%);
  }
  div {
    width: 200px;
    height: 200px;
    background: #243D83;
    border-radius: 50%;
    position: absolute;
    top: 50;
  }
  .c1 {
    left: -126;
  }
  .c2 {
    left: 100;
  }
  .c3 {
    right: -126;
  }
  .c1::before, .c1::after, .c2::before, .c2::after {
    content: '';
    height: 32px;
    width: 32px;
    border-radius: 50%;
    background: #6592CF;
    position: absolute;
    right: -29;
    top: 58;
  }
  .c1::after, .c2::after {
    top: 110;
  }
</style>
```
