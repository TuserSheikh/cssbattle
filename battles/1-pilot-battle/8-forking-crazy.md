# Battle #1 - Pilot Battle

## #8 - Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

![target](https://cssbattle.dev/targets/8.png)

```html
<div></div>
<style>
  body {
    background: #6592cf;
  }
  div {
    margin: 50px auto;
    width: 20px;
    height: 110px;
    border-radius: 10px;
    background: #6592cf;
    box-shadow: 20px 0 #060f55, -20px 0 #060f55, 40px 0 #6592cf, -40px 0 #6592cf, 60px 0 #060f55, -60px 0 #060f55,
      0 150px 0 #060f55;
  }
  div::before {
    content: "";
    height: 140px;
    width: 140px;
    border-radius: 0 0 50% 50%;
    background: #060f55;
    position: absolute;
    top: 110;
    left: 130;
    z-index: -1;
  }
</style>
```
