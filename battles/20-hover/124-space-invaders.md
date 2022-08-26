# Battle #20 - Hover

## #124 - Space Invaders

[Link to the problem](https://cssbattle.dev/play/124)

![target](https://cssbattle.dev/targets/124.png)

```html
<div class="space"></div>
<div class="fire"></div>
<div class="weapone"></div>
<style>
  body {
    background: #071945;
  }
  div {
    position: absolute;
  }
  .space {
    width: 50;
    height: 10;
    background: #b069f7;
    color: #b069f7;
    top: 40;
    left: 40;
    box-shadow: 90px 0, 180px 0, 270px 0, 0 50px #f8da37, 180px 50px #f8da37, 270px 50px #f8da37;
  }
  .fire {
    width: 10;
    height: 10;
    background: #b069f7;
    color: #b069f7;
    top: 50;
    left: 30;
    box-shadow: 60px 0, 90px 0, 150px 0, 180px 0, 240px 0, 270px 0, 330px 0, 0 50px #f8da37, 60px 50px #f8da37, 180px
        50px #f8da37, 240px 50px #f8da37, 270px 50px #f8da37, 330px 50px #f8da37, 165px 160px #2ce1ea,
      165px 190px #2ce1ea, 165px 220px #2ce1ea, 165px 230px #2ce1ea;
  }
  .weapone {
    width: 30;
    height: 30;
    background: #2ce1ea;
    transform: rotate(45deg);
    left: 185;
    bottom: -15;
  }
</style>
```
