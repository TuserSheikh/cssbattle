# Battle #12 - Blend

## #63 - Command Key

[Link to the problem](https://cssbattle.dev/play/63)

![target](https://cssbattle.dev/targets/63.png)

```html
<main>
  <div class="one"></div>
  <div class="two"></div>
  <div class="three"></div>
  <div class="four"></div>
</main>
<style>
  * {
    background: #191919;
  }
  main,
  div {
    width: 70;
    height: 70;
    box-sizing: border-box;
    border: 10px solid #5dbcf9;
  }
  main {
    position: relative;
    left: 158;
    top: 106;
  }
  div {
    position: absolute;
  }
  .one {
    inset: -70px;
    border-radius: 50px 50px 0;
  }
  .two {
    inset: -70px 50px;
    border-radius: 50px 50px 50px 0;
  }
  .three {
    inset: 50px -70px;
    border-radius: 50px 0 50px 50px;
  }
  .four {
    inset: 50px;
    border-radius: 0 50px 50px;
  }
</style>
```
