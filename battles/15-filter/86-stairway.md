# Battle #15 - Filter

## #86 - Stairway

[Link to the problem](https://cssbattle.dev/play/86)

![target](https://cssbattle.dev/targets/86.png)

```html
<div></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 100px;
    height: 150px;
    background: #4f77ff;
    border-radius: 100px 100px 0 0;
    position: relative;
  }
  div::after {
    content: "";
    position: absolute;
    right: 0;
    bottom: 0;
    width: 80px;
    height: 20px;
    background: #191919;
    box-shadow: 20px -24px #191919, 40px -48px #191919, 60px -72px #191919;
  }
</style>
```
