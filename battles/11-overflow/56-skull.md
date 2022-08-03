# Battle #11 - Overflow

## #56 - Skull

[Link to the problem](https://cssbattle.dev/play/56)

![target](https://cssbattle.dev/targets/56.png)

```html
<div class="container">
  <div class="eye"></div>
  <div class="nose"></div>
  <div class="teeth"></div>
</div>
<style>
  body {
    background: #191919;
    margin: 0;
  }
  .container::before {
    content: "";
    width: 120px;
    height: 100px;
    background: #4f77ff;
    position: absolute;
    top: -55px;
    left: -20px;
    border-radius: 60px 60px 10px 10px;
  }
  .container {
    width: 80px;
    height: 75px;
    background: #4f77ff;
    position: relative;
    top: 140px;
    left: 160px;
    border-radius: 10px 10px 20px 20px;
  }
  .eye,
  .nose,
  .teeth {
    background: #191919;
    position: absolute;
  }
  .eye {
    width: 40px;
    height: 40px;
    top: -2px;
    left: -5px;
    border-radius: 50%;
    box-shadow: 50px 0 #191919;
  }
  .nose {
    width: 20px;
    height: 20px;
    top: 36px;
    left: 30px;
    border-radius: 50%;
  }
  .teeth {
    width: 10px;
    height: 20px;
    top: 65px;
    left: 20px;
    border-radius: 20px;
    box-shadow: 15px 0 #191919, 30px 0 #191919;
  }
</style>
```
