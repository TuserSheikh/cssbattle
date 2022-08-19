# Battle #15 - Filter

## #88 - Tight Corner

[Link to the problem](https://cssbattle.dev/play/88)

![target](https://cssbattle.dev/targets/88.png)

```html
<div class="top"></div>
<div class="bottom"></div>
<style>
  body {
    margin: 0;
    background: linear-gradient(#f7f3da 40%, #d25b70 40% 60%, #f7f3da 60%);
  }
  .top,
  .bottom {
    width: 50%;
    height: 50%;
    background: #f7f3da;
    position: absolute;
  }
  .top {
    right: 0;
    border-radius: 0 0 0 20px;
  }
  .bottom {
    bottom: 0;
    border-radius: 0 20px 0 0;
  }
  .top::after,
  .bottom::after {
    content: "";
    width: 100%;
    height: 40;
    background: #d25b70;
    position: absolute;
  }
  .top::after {
    bottom: 0;
    left: -100%;
    border-radius: 0 10px 0 0;
  }
  .bottom::after {
    right: -100%;
    border-radius: 0 0 0 10px;
  }
</style>
```
