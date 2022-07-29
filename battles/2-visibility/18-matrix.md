# Battle #2 - Visibility

## #18 - Matrix

[Link to the problem](https://cssbattle.dev/play/18)

![target](https://cssbattle.dev/targets/18.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #5c434c;
    margin: 10px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    height: 100%;
    gap: 20px;
  }
  div {
    width: 80px;
    height: 80px;
    border-radius: 80px 0 0 0;
    background: #f09462;
  }
  div:nth-child(even) {
    background: #f5d6b4;
  }
</style>
```
