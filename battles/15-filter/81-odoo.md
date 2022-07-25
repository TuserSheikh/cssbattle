# Battle #15 - Filter

## #81 - Odoo

[Link to the problem](https://cssbattle.dev/play/81)

![target](https://cssbattle.dev/targets/81.png)

```html
<main>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</main>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
  }
  main {
    position: absolute;
    top: 102;
    width: 330px;
    height: 120px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }
  div {
    top: 100;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    border: 20px solid #8F8F8F;
    box-sizing: border-box;
  }
  div:first-child {
    border-color: #714B67;
  }
  div:nth-child(2)::after {
    content: '';
    height: 70px;
    width: 20px;
    background: #8F8F8F;
    position: absolute;
    left: 144;
    top: 0;
    border-radius: 30px;
  }
</style>
```
