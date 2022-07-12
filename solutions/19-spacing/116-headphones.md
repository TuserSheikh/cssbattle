# Battle #7 - Spacing

## #116 - Headphones

[Link to the problem](https://cssbattle.dev/play/116)

![result](https://cssbattle.dev/targets/116.png)

```html
<div></div>
<style>
  body {
    background: #293d7e;
    display: flex;
    justify-content: center;
  }
  div {
    position: absolute;
    top: 45;
    width: 130px;
    height: 100px;
    border-radius: 85px 85px 0 0;
    border: 20px solid #6e91ca;
    border-bottom: 0;
  }
  div::before,
  div::after {
    content: "";
    width: 60px;
    height: 80px;
    background: #6e91ca;
    position: absolute;
    top: 100;
  }
  div::before {
    left: -20;
    border-radius: 0 35px 50px 50px;
  }
  div::after {
    right: -20;
    border-radius: 35px 0 50px 50px;
  }
</style>
```
