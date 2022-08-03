# Battle #13 - Clip

## #70 - Froggy

[Link to the problem](https://cssbattle.dev/play/70)

![target](https://cssbattle.dev/targets/70.png)

```html
<main>
  <div class="eye left"></div>
  <div class="eye right"></div>
  <div class="nose"></div>
</main>
<style>
  body {
    background: #293462;
  }
  main {
    width: 150px;
    height: 100px;
    background: radial-gradient(circle at 50% -130px, #fe5f55 200px, #a64942 200px);
    position: relative;
    top: 102px;
    left: 117px;
    border-radius: 50px;
  }
  .eye {
    content: "";
    width: 30px;
    height: 30px;
    background: #293462;
    position: absolute;
    border-radius: 50%;
    top: -15px;
    box-sizing: border-box;
    border: 10px solid #fff1c1;
    box-shadow: 0 0 0 10px #fe5f55;
  }
  .eye.left {
    left: 25;
  }
  .eye.right {
    right: 25;
  }
  .nose {
    width: 10px;
    height: 10px;
    background: #293462;
    position: absolute;
    border-radius: 50%;
    bottom: 40px;
    left: 60px;
    box-shadow: 20px 0 #293462;
  }
</style>
```
