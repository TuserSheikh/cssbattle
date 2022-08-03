# Battle #11 - Overflow

## #57 - Pillars

[Link to the problem](https://cssbattle.dev/play/57)

![target](https://cssbattle.dev/targets/57.png)

```html
<main>
  <div></div>
</main>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  main {
    width: 110px;
    height: 110px;
    background: #4f77ff;
    position: relative;
  }
  div {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #191919;
    position: absolute;
    top: -20px;
    left: -20px;
    box-shadow: 90px 0 #191919, 0 90px #191919, 90px 90px #191919;
  }
  div::before {
    content: "";
    width: 45px;
    height: 45px;
    border-radius: 50%;
    background: #f9e492;
    position: absolute;
    box-shadow: 105px 0 #f9e492, 0 105px #f9e492, 105px 105px #f9e492;
  }
  div::after {
    content: "";
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #4f77ff;
    position: absolute;
    box-shadow: 120px 0 #4f77ff, 0 120px #4f77ff, 120px 120px #4f77ff;
  }
</style>
```
