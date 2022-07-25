# Battle #14 - ZIndex

## #80. Piano

[Link to the problem](https://cssbattle.dev/play/80)

![target](https://cssbattle.dev/targets/80.png)

```html
<div class="piano">
  <div class="key"></div>
  <div class="key"></div>
  <div class="key"></div>
  <div class="key"></div>
  <div class="key"></div>
  <div class="key"></div>
  <div class="key"></div>
</div>
<style>
  body {
    background: #998235;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .piano {
    border-radius: 10px;
    width: 180px;
    height: 100px;
    background: #191919;
    display: flex;
    align-items: flex-end;
    justify-content: space-evenly;
    position: relative;
  }
  .key {
    width: 20px;
    background: #ffffff;
    height: 70px;
    margin-bottom: 5px;
    border-radius: 5px;
  }
  .key:not(:last-child, :nth-child(3))::after {
    content: "";
    position: absolute;
    width: 15px;
    background: #191919;
    height: 60px;
    top: 0;
    margin-left: 15px;
  }
</style>
```
