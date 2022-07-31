# Battle #8 - Transition

## #42 - Baby

[Link to the problem](https://cssbattle.dev/play/42)

![target](https://cssbattle.dev/targets/42.png)

```html
<div class="head">
  <div class="hair"></div>
  <div class="eye"></div>
  <div class="mouth"></div>
</div>
<style>
  body {
    background: #293462;
    display: grid;
    place-items: center;
  }
  .head {
    width: 200px;
    height: 200px;
    background: #fe5f55;
    border-radius: 100px 100px 50px 50px;
    position: relative;
    overflow: hidden;
  }
  .hair,
  .eye,
  .mouth {
    position: absolute;
    background: #fff1c1;
  }
  .hair {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    top: -50px;
    box-shadow: 100px 0 #fff1c1;
  }
  .eye {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    top: 90px;
    left: 20px;
    box-shadow: 100px 0 #fff1c1;
  }
  .mouth {
    width: 40px;
    height: 10px;
    border-radius: 10px;
    top: 170px;
    left: 80px;
  }
</style>
```
