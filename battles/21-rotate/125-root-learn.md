# Battle #20 - Rotate

## #125 - Root Learn

[Link to the problem](https://cssbattle.dev/play/125)

![target](https://cssbattle.dev/targets/125.png)

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #eff2f1;
  }
  div {
    position: absolute;
  }
  [a] {
    left: 130;
    top: 60;
    width: 40;
    height: 180;
    background: #1c1c1c;
    -webkit-box-reflect: right -40px;
  }
  [a]::before,
  [a]::after {
    content: "";
    position: absolute;
    left: -20;
    width: 20;
    height: 20;
    background: #1c1c1c;
  }
  [a]::before {
    top: 0;
    clip-path: polygon(0 45%, 100% 103%, 100% 0, 0 0);
  }
  [a]::after {
    bottom: 0;
    clip-path: polygon(100% -3%, 100% 100%, 0 100%, 0 55%);
  }
  [b] {
    left: 170;
    top: 60;
    width: 90;
    height: 90;
    border-radius: 0 50% 50% 0;
    background: #1c1c1c;
  }
  [b]::after {
    content: "";
    position: absolute;
    left: 0;
    top: 15;
    width: 50;
    height: 60;
    background: #eff2f1;
    border-radius: 0 50px 50px 0;
  }
  [c] {
    left: 203;
    top: 140;
    width: 46;
    height: 100;
    background: #1c1c1c;
    transform: skew(30deg);
  }
  [c]::after {
    content: "";
    position: absolute;
    right: -15;
    bottom: 0;
    width: 20;
    height: 25;
    background: #1c1c1c;
    clip-path: polygon(0% 0, 100% 75%, 85% 100%, 0 100%);
  }
</style>
```
