# Battle #2 - Visibility

## #16 - Eye of the Tiger

[Link to the problem](https://cssbattle.dev/play/16)

![target](https://cssbattle.dev/targets/16.png)

```html
<div class="outer">
  <div class="inner"></div>
</div>
<style>
  body {
    display: grid;
    place-items: center;
    background: #0b2429;
  }
  .outer {
    width: 200px;
    height: 200px;
    background: #998235;
    border-radius: 0 100px;
    transform: rotate(-45deg);
    display: grid;
    place-items: center;
  }
  .inner {
    background: #0b2429;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    border: 45px solid #f3ac3c;
    box-shadow: 0 0 0 20px #0b2429;
  }
</style>
```
