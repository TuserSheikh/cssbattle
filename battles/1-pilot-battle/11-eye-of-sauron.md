# Battle #1 - Pilot Battle

## #11 - Eye of Sauron

[Link to the problem](https://cssbattle.dev/play/11)

![target](https://cssbattle.dev/targets/11.png)

```html
<div></div>
<style>
  body {
    background: #191210;
    display: grid;
    place-items: center;
  }
  div {
    height: 100px;
    width: 100px;
    background: #84271c;
    border: 25px solid #191210;
    border-radius: 50%;
    box-sizing: border-box;
    box-shadow: 0 0 0 20px #eca03d;
    position: relative;
  }
  div::before,
  div::after {
    content: "";
    position: absolute;
    height: 50px;
    width: 100px;
    border-radius: 0 0 50px 50px;
    border: 20px solid #eca03d;
    border-top: 0;
    box-sizing: border-box;
  }
  div::before {
    top: 25;
    left: -125;
  }
  div::after {
    top: -25;
    right: -125;
    transform: rotate(180deg);
  }
</style>
```
