# Battle #17 - Chrismas

## #97 - Snowman

[Link to the problem](https://cssbattle.dev/play/97)

![target](https://cssbattle.dev/targets/97.png)

```html
<div class="cap-top"></div>
<div class="cap-bottom"></div>
<div class="head"></div>
<div class="neck"></div>
<div class="body"></div>
<div></div>
<style>
  body {
    background: #ac474b;
    display: flex;
    justify-content: center;
  }
  .cap-top {
    width: 40px;
    height: 40px;
    background: linear-gradient(#0e1f2b 37%, #ffffff 37%, #ffffff 63%, #0e1f2b 63%);
    position: absolute;
    top: 55;
  }
  .cap-bottom {
    width: 60px;
    height: 5px;
    background: #0e1f2b;
    position: absolute;
    top: 95;
  }
  .head {
    width: 60px;
    height: 60px;
    background: #ffffff;
    position: absolute;
    top: 95;
    border-radius: 50%;
    z-index: -1;
  }
  .head::before,
  .head::after {
    content: "";
    width: 10px;
    height: 10px;
    background: #0e1f2b;
    position: absolute;
    top: 18;
    border-radius: 50%;
  }
  .head::before {
    left: 15;
  }
  .head::after {
    right: 15;
  }
  .neck {
    width: 60px;
    height: 10px;
    background: #ffa63f;
    position: absolute;
    top: 139;
    border: 4px solid #ac474b;
    border-radius: 10px;
  }
  .body {
    width: 100px;
    height: 100px;
    background: #ffffff;
    position: absolute;
    top: 145;
    border-radius: 50%;
    z-index: -1;
  }
</style>
```
