# Battle #18 - Float

## #104 - Amegakure

[Link to the problem](https://cssbattle.dev/play/104)

![target](https://cssbattle.dev/targets/104.png)

```html
<div class="outer">
  <div class="inner">
    <div class="dc">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot"></div>
    </div>
    <div class="mid">
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
    </div>
    <div class="dc">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot"></div>
    </div>
  </div>
</div>
<style>
  body {
    background: #000000;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .outer {
    width: 240px;
    height: 120px;
    background: #37385a;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .inner {
    width: 200px;
    height: 80px;
    background: linear-gradient(-75deg, #9897ae 82px, #c0c3db 82px, #c0c3db 132px, #9897ae 132px);
    border-radius: 10px;
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .dc {
    width: 20px;
    height: 50px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }
  .dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #000000;
  }
  .mid {
    width: 100px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .bar {
    margin: 0 5px;
    width: 10px;
    height: 50px;
    border-radius: 50px;
    background: #000000;
  }
</style>
```
