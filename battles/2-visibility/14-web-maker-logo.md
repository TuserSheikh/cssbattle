# Battle #2 - Visibility

## #14 - Web Maker Logo

[Link to the problem](https://cssbattle.dev/play/14)

![target](https://cssbattle.dev/targets/14.png)

```html
<div></div>
<div></div>
<style>
  body {
    background: #f2f2b6;
  }
  div {
    position: absolute;
    top: 85px;
    left: 60px;
    border-top: 130px solid #ff6d00;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    filter: drop-shadow(20px 0 #fd4602);
  }
  div:last-of-type {
    left: 170px;
    border-top: 130px solid #fd4602;
    filter: drop-shadow(-20px 0 #ff6d00);
    transform: scale(-1);
  }
</style>
```
