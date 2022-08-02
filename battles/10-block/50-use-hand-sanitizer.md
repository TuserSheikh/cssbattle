# Battle #10 - Block

## #50 - Use Hand Sanitizer

[Link to the problem](https://cssbattle.dev/play/50)

![target](https://cssbattle.dev/targets/50.png)

```html
<div class="liquid"></div>
<div class="mouth"></div>
<div class="handle"></div>
<div class="bottol-top"></div>
<div class="bottol"></div>
<style>
  body {
    background: #1a4341;
    margin: 0;
  }
  .liquid {
    width: 20px;
    height: 20px;
    background: #998235;
    position: absolute;
    top: 100px;
    left: 280px;
    border-radius: 20px;
    box-shadow: 0 30px #998235;
  }
  .mouth {
    width: 20px;
    height: 40px;
    background: #f3ac3c;
    position: absolute;
    top: 50px;
    left: 280px;
    border-radius: 20px;
    box-shadow: -90px 10px #f3ac3c;
  }
  .handle {
    width: 150px;
    height: 20px;
    background: #f3ac3c;
    position: absolute;
    top: 50px;
    left: 150px;
    border-radius: 20px;
  }
  .bottol-top {
    width: 50px;
    height: 20px;
    background: #f3ac3c;
    position: absolute;
    top: 90px;
    left: 175px;
    border-radius: 10px 10px 0 0;
  }
  .bottol {
    width: 100px;
    height: 140px;
    position: relative;
    top: 110px;
    left: 150px;
    background: linear-gradient(90deg, #f3ac3c 50%, #998235 50%);
    border-radius: 20px;
  }
  .bottol::before,
  .bottol::after {
    content: "";
    position: absolute;
    width: 50%;
  }
  .bottol::before {
    bottom: 0;
    border-radius: 35px 35px 0 25px;
    background: #998235;
    height: 78.5%;
  }
  .bottol::after {
    right: 0;
    border-radius: 0 25px 35px 35px;
    background: #f3ac3c;
    height: 57%;
  }
</style>
```
