# Battle #18 - Float

## #108 - Clow Card

[Link to the problem](https://cssbattle.dev/play/108)

![target](https://cssbattle.dev/targets/108.png)

```html
<main>
  <div class="black">
    <div class="center"></div>
  </div>
</main>
<style>
  body {
    background: #000000;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  main {
    width: 300px;
    height: 150px;
    background: linear-gradient(
      105deg,
      #e96a23 120px,
      #ebae11 120px,
      #ebae11 170px,
      #e96a23 170px,
      #e96a23 184px,
      #ebae11 184px,
      #ebae11 209px,
      #e96a23 209px
    );
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .black {
    width: 240px;
    height: 120px;
    border-radius: 13px;
    background: #000000;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .black::before {
    content: "";
    position: absolute;
    width: 270px;
    height: 90px;
    border-radius: 13px;
    background: #000000;
  }
  .black::after {
    content: "";
    position: absolute;
    width: 200px;
    height: 80px;
    border-radius: 50%;
    border: 5px solid #ebae11;
  }
  .center {
    position: absolute;
    width: 120px;
    height: 60px;
    border-radius: 50%;
    border: 5px solid #ebae11;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .center::after {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #ebae11;
  }
</style>
```
