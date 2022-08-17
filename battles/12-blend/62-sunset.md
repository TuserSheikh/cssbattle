# Battle #12 - Blend

## #62 - Sunset

[Link to the problem](https://cssbattle.dev/play/62)

![target](https://cssbattle.dev/targets/62.png)

```html
<main>
  <div></div>
</main>
<style>
  body {
    display: grid;
    place-items: center;
    background: #191919;
  }
  main {
    width: 150;
    height: 200;
    background: #f2ad43;
    border-radius: 80px 80px 21px 21px;
    position: relative;
    overflow: hidden;
  }
  div {
    width: 60;
    height: 60;
    background: #fff58f;
    border-radius: 50%;
    position: absolute;
    left: 45;
    top: 90;
  }
  div::before,
  div::after {
    content: "";
    width: 200;
    height: 200;
    position: absolute;
    bottom: -150;
    border-radius: 50%;
  }
  div::before {
    background: #e08027;
    left: -145;
  }
  div::after {
    background: #824b20;
    right: -145;
  }
</style>
```
