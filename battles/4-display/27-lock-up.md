# Battle #4 - Display

## #27 - Lock Up

[Link to the problem](https://cssbattle.dev/play/27)

![target](https://cssbattle.dev/targets/27.png)

```html
<div></div>
<style>
  body {
    background: #e38f66;
    display: grid;
    place-items: center;
  }
  div {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: repeating-conic-gradient(#f7ec7d 0%, #f7ec7d 25%, #aa445f 25%, #aa445f 50%);
    border: 30px solid #aa445f;
    display: grid;
    place-items: center;
  }
  div::after {
    content: "";
    position: absolute;
    background: #aa445f;
    width: 80px;
    height: 80px;
    border-radius: 50%;
  }
</style>
```
