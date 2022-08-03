# Battle #13 - Clip

## #76 - Beeee

[Link to the problem](https://cssbattle.dev/play/76)

![target](https://cssbattle.dev/targets/76.png)

```html
<main>
  <div class="left"></div>
  <div class="right"></div>
  <div class="bee"></div>
</main>
<style>
  body {
    background: #998235;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  main {
    width: 150px;
    height: 150px;
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .left {
    background: #ffffff;
    border-radius: 50px 50px 0 50px;
  }
  .right {
    background: #ffffff;
    border-radius: 50px 50px 50px 0;
  }
  .bee {
    grid-column: 1 / 3;
    border-radius: 50px;
    background: linear-gradient(
      to right,
      #191919 25px,
      #eff33c 25px,
      #eff33c 35px,
      #191919 35px,
      #191919 60px,
      #eff33c 60px,
      #eff33c 70px,
      #191919 70px,
      #191919 95px,
      #eff33c 95px
    );
  }
  .bee::after {
    content: "";
    position: absolute;
    top: 170;
    right: 145;
    height: 15px;
    width: 15px;
    border-radius: 50%;
    background: #191919;
  }
</style>
```
