# Battle #10 - Block

## #52 - Break the Chain

[Link to the problem](https://cssbattle.dev/play/52)

![target](https://cssbattle.dev/targets/52.png)

```html
<div class="left">
  <div class="tree"></div>
  <div class="tree"></div>
  <div class="tree"></div>
</div>
<div class="right">
  <div class="tree"></div>
  <div class="tree"></div>
  <div class="tree"></div>
  <div class="tree"></div>
</div>
<style>
  body {
    background: #6592cf;
  }
  .left,
  .right {
    position: absolute;
    top: 140px;
    display: flex;
    justify-content: space-between;
  }
  .left {
    left: 45px;
    width: 100px;
  }
  .right {
    left: 210px;
    width: 145px;
  }
  .tree {
    height: 50px;
    width: 10px;
    background: #243d83;
  }
  .tree::before,
  .tree::after {
    content: "";
    border-radius: 50%;
    position: absolute;
  }
  .tree::before {
    height: 20px;
    width: 20px;
    background: #243d83;
    margin-top: -10px;
    margin-left: -5px;
  }
  .left .tree:nth-child(odd)::after {
    height: 40px;
    width: 40px;
    background: #eeb850;
    margin-top: -20px;
    margin-left: -15px;
    z-index: -1;
  }
  .left .tree:nth-child(2)::after {
    height: 60px;
    width: 60px;
    background: #eeb850;
    margin-top: -40px;
    margin-left: -25px;
    z-index: -1;
  }
</style>
```
