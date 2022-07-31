# Battle #9 - Margin

## #45 - Magical Tree

[Link to the problem](https://cssbattle.dev/play/45)

![target](https://cssbattle.dev/targets/45.png)

```html
<div></div>
<style>
  body {
    margin: 0;
    background: #1a4341;
    display: flex;
    justify-content: center;
  }
  div {
    width: 90px;
    height: 120px;
    background: #1a4341;
    border: 30px solid #998235;
    border-top: 0;
    box-shadow: 0 0 0 30px #1a4341, 0 0 0 60px #f3ac3c;
    display: flex;
    justify-content: center;
  }
  div::before,
  div::after {
    content: "";
    position: absolute;
  }
  div::before {
    width: 270px;
    height: 30px;
    background: #998235;
    top: 240;
  }
  div::after {
    width: 30px;
    height: 100%;
    background: #f3ac3c;
  }
</style>
```
