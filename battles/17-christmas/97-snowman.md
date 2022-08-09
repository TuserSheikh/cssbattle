# Battle #17 - Chrismas

## #97 - Snowman

[Link to the problem](https://cssbattle.dev/play/97)

![target](https://cssbattle.dev/targets/97.png)

```html
<div class="body"></div>
<div class="head"></div>
<div class="cap"></div>
<div></div>
<style>
  body {
    background: #AC474B;
    display: flex;
    justify-content: center;
  }
  .cap {
    width: 40px;
    height: 40px;
    background: linear-gradient(#0E1F2B 37%, #FFF 37% 63%, #0E1F2B 63%);
    position: absolute;
    top: 55px;
  }
  .cap::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: -10px;
    width: 60px;
    height: 5px;
    background: #0E1F2B;
  }
  .head {
    width: 60px;
    height: 60px;
    background: #FFF;
    position: absolute;
    top: 95px;
    border-radius: 50%;
  }
  .head::before {
    content: '';
    width: 10px;
    height: 10px;
    background: #0E1F2B;
    position: absolute;
    top: 18px;
    left: 15px;
    border-radius: 50%;
    box-shadow: 20px 0 #0E1F2B;
  }
  .head::after {
    content: '';
    width: 60px;
    height: 10px;
    background: #FFA63F;
    position: absolute;
    bottom: 2;
    border-radius: 10px;
    box-shadow: 10px 0 0 4px #AC474B, -10px 0 0 4px #AC474B;
  }
  .body {
    width: 100px;
    height: 100px;
    background: #FFF;
    position: absolute;
    top: 145px;
    border-radius: 50%;
  }
</style>
</style>
```
