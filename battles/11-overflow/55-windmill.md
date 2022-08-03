# Battle #11 - Overflow

## #55 - Windmill

[Link to the problem](https://cssbattle.dev/play/55)

![target](https://cssbattle.dev/targets/55.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="four"></div>
<style>
  body {
    background: #191919;
  }
  div {
    width: 100px;
    height: 50px;
    border-radius: 50px 50px 0 0;
    position: absolute;
  }
  .one {
    top: 100px;
    left: 100px;
    background: #f9e492;
  }
  .two {
    top: 75px;
    left: 175px;
    background: #4f77ff;
    transform: rotate(90deg);
  }
  .three {
    top: 150px;
    left: 200px;
    background: #f9e492;
    transform: rotate(180deg);
  }
  .four {
    top: 175px;
    left: 125px;
    background: #4f77ff;
    transform: rotate(270deg);
  }
</style>
```
