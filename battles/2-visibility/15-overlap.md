# Battle #2 - Visibility

## #15 - Overlap

[Link to the problem](https://cssbattle.dev/play/15)

![target](https://cssbattle.dev/targets/15.png)

```html
<div></div>
<style>
  body {
    background: #09042a;
  }
  div {
    width: 150;
    height: 150;
    background: #7b3f61;
    border-radius: 50%;
    position: absolute;
    top: 75px;
    left: 75px;
    box-shadow: 100px 0 0 0 #e78481;
    overflow: hidden;
  }
  div::after {
    content: "";
    position: absolute;
    width: 150;
    height: 150;
    background: #09042a;
    border-radius: 50%;
    left: 100px;
  }
</style>
```
