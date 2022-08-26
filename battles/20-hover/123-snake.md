# Battle #20 - Hover

## #123 - Snake

[Link to the problem](https://cssbattle.dev/play/123)

![target](https://cssbattle.dev/targets/123.png)

```html
<div class="food"></div>
<div class="snake"></div>
<style>
  body {
    background: #c74e4e;
  }
  div {
    width: 20;
    height: 20;
    position: absolute;
    top: 90;
  }
  .food {
    background: #fff;
    border-radius: 50%;
    left: 90;
  }
  .snake {
    background: #e0e246;
    color: #e0e246;
    border-radius: 5px;
    left: 190;
    box-shadow: 25px 0, 50px 0, 75px 0, 100px 0, 100px 25px, 100px 50px, 100px 75px, 100px 100px, 75px 100px, 50px 100px,
      25px 100px, 0 100px, -25px 100px, -50px 100px, -75px 100px, -100px 100px;
  }
</style>
```
