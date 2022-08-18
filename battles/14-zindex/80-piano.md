# Battle #14 - ZIndex

## #80. Piano

[Link to the problem](https://cssbattle.dev/play/80)

![target](https://cssbattle.dev/targets/80.png)

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  body {
    background: #998235;
    display: grid;
    place-items: center;
  }
  main {
    border-radius: 10px;
    width: 180;
    height: 100;
    background: #191919;
    display: flex;
    align-items: flex-end;
    justify-content: space-evenly;
    position: relative;
  }
  div {
    width: 20;
    background: #fff;
    height: 70;
    margin-bottom: 5;
    border-radius: 5px;
  }
  div:not(:last-child, :nth-child(3))::after {
    content: "";
    position: absolute;
    width: 15;
    background: #191919;
    height: 60;
    top: 0;
    margin-left: 15;
  }
</style>
```
