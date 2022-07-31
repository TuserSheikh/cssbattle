# Battle #4 - Display

## #21 - SitePoint Logo

[Link to the problem](https://cssbattle.dev/play/21)

![target](https://cssbattle.dev/targets/21.png)

```html
<div></div>
<div></div>
<style>
  body {
    background: #222;
  }
  div {
    position: absolute;
    top: 58px;
    left: 155px;
    background: #f2994a;
    width: 30px;
    height: 100px;
    transform: rotate(45deg);
    border-radius: 0 0 0 10px;
  }
  div::after {
    content: "";
    position: absolute;
    top: 50px;
    left: 30px;
    background: #f2994a;
    width: 30px;
    height: 70px;
    transform: rotate(90deg);
    border-radius: 5px 0 0 0;
  }
  div:last-of-type {
    background: #2d9cdb;
    transform: rotate(225deg);
    top: 142px;
    left: 213px;
  }
  div:last-of-type::after {
    background: #2d9cdb;
  }
</style>
```
