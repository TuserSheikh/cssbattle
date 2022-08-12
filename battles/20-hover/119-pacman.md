# Battle #20 - Hover

## #119 - Pacman

[Link to the problem](https://cssbattle.dev/play/119)

![target](https://cssbattle.dev/targets/119.png)

```html
<div class="pac-man"></div>
<div class="dot"></div>
<div class="ghost"></div>
<style>
  body {
    background: #000;
    display: flex;
    align-items: center;
  }
  div {
    position: absolute;
  }
  .pac-man {
    width: 60;
    height: 60;
    background: #e0e246;
    border-radius: 50%;
    left: 60;
  }
  .pac-man::after {
    content: "";
    width: 60;
    height: 60;
    background: #000;
    position: absolute;
    transform: translate(66%) rotate(45deg);
  }
  .dot {
    width: 10;
    height: 10;
    background: #fff;
    border-radius: 50%;
    left: 165;
    box-shadow: 30px 0 #fff, 60px 0 #fff;
  }
  .ghost {
    width: 60;
    height: 60;
    background: #c74e4e;
    border-radius: 50px 50px 0 0;
    left: 280;
  }
  .ghost::after {
    content: "";
    width: 20;
    height: 20;
    background: #000;
    position: absolute;
    bottom: -12;
    transform: rotate(45deg);
    box-shadow: 14px -15px #000, 28px -29px #000;
  }
</style>
```
