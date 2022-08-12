# Battle #11 - Overflow

## #58 - Rose

[Link to the problem](https://cssbattle.dev/play/58)

![target](https://cssbattle.dev/targets/58.png)

```html
<div class="stem"></div>
<div class="hip"></div>
<div class="sepal"></div>
<div class="petal three"></div>
<div class="petal two"></div>
<div class="petal one"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
  }
  div {
    position: absolute;
    background: #4f77ff;
  }
  .stem {
    width: 20;
    height: 90;
    background: #f9e492;
    border-radius: 20px;
    top: 165;
  }
  .hip {
    width: 40;
    height: 40;
    background: #f9e492;
    border-radius: 50%;
    top: 145;
  }
  .sepal {
    width: 100;
    height: 50;
    border-radius: 0 0 50px 50px;
    top: 115;
  }
  .petal {
    box-shadow: 0 0 0 10px #191919;
    height: 30;
    border-radius: 5px 5px 30px 30px;
  }
  .petal.three {
    width: 140;
    top: 85;
  }
  .petal.two {
    width: 100;
    top: 65;
  }
  .petal.one {
    width: 30;
    border-radius: 50%;
    top: 45;
  }
</style>
```
