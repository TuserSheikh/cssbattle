# Battle #4 - Display

## #24 - Switches

[Link to the problem](https://cssbattle.dev/play/24)

![target](https://cssbattle.dev/targets/24.png)

```html
<div></div>
<div></div>
<style>
  body {
    background: #62306d;
  }
  div {
    height: 150px;
    width: 100px;
    background: #aa445f;
    position: absolute;
    top: 50px;
    left: 80px;
    border-radius: 100px;
  }
  div::after {
    content: "";
    position: absolute;
    bottom: 0;
    width: 100px;
    height: 100px;
    background: #f7ec7d;
    border-radius: 50%;
  }
  div:last-of-type {
    top: 100px;
    left: 220px;
    background: #e38f66;
    transform: scale(-1);
  }
</style>
```
