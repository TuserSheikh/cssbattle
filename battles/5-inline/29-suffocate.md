# Battle #5 - Inline

## #29 - Suffocate

[Link to the problem](https://cssbattle.dev/play/29)

![target](https://cssbattle.dev/targets/29.png)

```html
<div class="one"></div>
<div class="two"></div>
<div class="three"></div>
<div class="four"></div>
<style>
  body {
    margin: 0;
    background: #1a4341;
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  div {
    width: 100%;
    height: 100%;
    background: #f3ac3c;
  }
  .one {
    border-radius: 0 0 100px 0;
  }
  .two {
    border-radius: 0 0 0 100px;
  }
  .three {
    border-radius: 0 100px 0 0;
  }
  .four {
    border-radius: 100px 0 0 0;
  }
</style>
```
