# Battle #20 - Rotate

## #131 - Letter W

[Link to the problem](https://cssbattle.dev/play/131)

![target](https://cssbattle.dev/targets/131.png)

```html
<div></div>
<style>
  body {
    background: #e38f66;
  }
  div {
    position: absolute;
    top: 83;
    left: 95;
    width: 120;
    height: 147;
    border-radius: 0 0 60px 60px;
    border: 30px solid #62306d;
    box-sizing: border-box;
    border-top: 0;
    filter: drop-shadow(90px 0 #fffbda);
  }
  div::after {
    content: '';
    position: absolute;
    top: -13;
    left: -30;
    background: #62306d;
    width: 30;
    height: 30;
    border-radius: 50%;
    box-shadow: 90px 0 #62306d;
  }
</style>
```
