# Battle #15 - Filter

## #86 - Stairway

[Link to the problem](https://cssbattle.dev/play/86)

![target](https://cssbattle.dev/targets/86.png)

```html
<div></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    width: 100;
    height: 150;
    background: #4f77ff;
    border-radius: 100px 100px 0 0;
    position: relative;
  }
  div::after {
    content: "";
    position: absolute;
    right: 0;
    bottom: 0;
    width: 80;
    height: 20;
    background: #191919;
    color: #191919;
    box-shadow: 20px -24px, 40px -48px, 60px -72px;
  }
</style>
```
