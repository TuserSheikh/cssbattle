# Battle #10 - Block

## #51 - Wear a Mask

[Link to the problem](https://cssbattle.dev/play/51)

![target](https://cssbattle.dev/targets/51.png)

```html
<div class="rabbar"></div>
<div class="mask"></div>
<style>
  body {
    background: #293462;
    display: flex;
    justify-content: center;
  }
  .rabbar {
    width: 250px;
    height: 40px;
    background: #293462;
    position: absolute;
    top: 110;
    border-radius: 40px;
    box-shadow: 0 0 0 10px #fff1c1;
  }
  .mask {
    background: #fff1c1;
    width: 150px;
    height: 92px;
    position: relative;
    top: 100;
    border-radius: 0 0 50px 50px;
  }
  .mask::before,
  .mask::after {
    content: "";
    background: #fe5f55;
    position: absolute;
    width: 40px;
  }
  .mask::before {
    height: 10px;
    top: 12px;
    left: 20px;
    border-radius: 50px;
    box-shadow: 0 20px #fe5f55;
  }
  .mask::after {
    height: 40px;
    border-radius: 50%;
    right: 20px;
    top: 32px;
  }
</style>
```
