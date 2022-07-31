# Battle #7 - Backface

## #36 - Interleaved

[Link to the problem](https://cssbattle.dev/play/36)

![target](https://cssbattle.dev/targets/36.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #1a4341;
    margin: 0;
    display: flex;
    justify-content: space-evenly;
  }
  div {
    width: 50px;
    height: 200px;
    background: #f3ac3c;
  }
  div:nth-child(odd) {
    border-radius: 50px 50px 0 0;
    align-self: flex-end;
  }
  div:nth-child(even) {
    border-radius: 0 0 50px 50px;
    background: #998235;
  }
</style>
```
