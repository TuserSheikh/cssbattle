# Battle #16 - Aspect

## #94 - Ripples

[Link to the problem](https://cssbattle.dev/play/94)

![target](https://cssbattle.dev/targets/94.png)

```html
<div class="outer"></div>
<div class="inner"></div>
<style>
  body {
    background: #0e2e2c;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .inner {
    position: absolute;
    width: 40px;
    height: 40px;
    background: #f3ac3c;
    border-radius: 50%;
    box-shadow: 0 0 0 8px #0e2e2c, 0 0 0 20px #f3ac3c;
  }
  .outer {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #0e2e2c;
    border-radius: 50%;
    box-shadow: 0 0 0 10px #998235, 0 0 0 22px #0e2e2c, 0 0 0 30px #f3ac3c, 0 0 0 44px #0e2e2c, 0 0 0 50px #f3ac3c;
  }
</style>
```
