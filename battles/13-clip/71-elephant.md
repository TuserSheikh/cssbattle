# Battle #13 - Clip

## #71 - Elephant

[Link to the problem](https://cssbattle.dev/play/71)

![target](https://cssbattle.dev/targets/71.png)

```html
<div class="ear"></div>
<div class="face"></div>
<div class="eye"></div>
<div class="tusk"></div>
<div class="trunk"></div>
<style>
  body {
    background: #998235;
  }
  div {
    position: absolute;
  }
  .ear {
    top: 60;
    left: 50;
    width: 80;
    height: 180;
    border-radius: 50%;
    background: #0b2429;
    box-shadow: inset 16px 0 #1a4341;
    -webkit-box-reflect: right 140px;
  }
  .face {
    width: 180;
    height: 180;
    border-radius: 50%;
    background: #1a4341;
    top: 60;
    left: 110;
  }
  .eye {
    width: 20;
    height: 10;
    border-radius: 0 0 50px 50px;
    background: #0b2429;
    top: 150;
    left: 150;
    border: 10px solid #998235;
    border-top: 0;
    -webkit-box-reflect: right 20px;
  }
  .tusk {
    width: 80;
    height: 40;
    border-radius: 60px 60px 0 0;
    top: 190;
    left: 140;
    border: 20px solid #fff;
    border-bottom: 0;
  }
  .trunk {
    width: 40;
    height: 200;
    border-radius: 40px;
    top: 180;
    left: 180;
    background: #0b2429;
  }
</style>
```
