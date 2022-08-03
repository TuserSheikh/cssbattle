# Battle #11 - Overflow

## #54 - Black Lives Matter

[Link to the problem](https://cssbattle.dev/play/54)

![target](https://cssbattle.dev/targets/54.png)

```html
<div class="fingers">
  <div class="finger one"></div>
  <div class="finger two"></div>
  <div class="finger three"></div>
  <div class="finger four"></div>
</div>
<div class="palm"></div>
<div class="wrist"></div>
<style>
  body {
    background: #f9e492;
    margin: 0;
  }
  .fingers {
    width: 95px;
    height: 60px;
    position: relative;
    bottom: -73px;
    left: 155px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
  }
  .finger {
    width: 20px;
    background: #191919;
    border-radius: 50px;
  }
  .one,
  .three {
    height: 75%;
  }
  .two {
    height: 91%;
  }
  .four {
    height: 58%;
  }
  .palm {
    width: 100px;
    height: 40px;
    background: #191919;
    position: absolute;
    top: 138px;
    left: 150px;
    border-radius: 0 0 10px 10px;
  }
  .palm::after {
    content: "";
    width: 20px;
    height: 65px;
    background: #191919;
    border-radius: 50px;
    border: 5px solid #f9e492;
    position: absolute;
    top: -34px;
    left: 2px;
    transform: rotate(60deg);
  }
  .wrist {
    width: 50px;
    height: 50px;
    background: #191919;
    position: absolute;
    top: 173px;
    left: 175px;
    border-radius: 0 0 10px 10px;
  }
</style>
```
