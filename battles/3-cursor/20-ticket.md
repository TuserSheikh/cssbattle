# Battle #3 - Cursor

## #20 - Ticket

[Link to the problem](https://cssbattle.dev/play/20)

![target](https://cssbattle.dev/targets/20.png)

```html
<div></div>
<style>
  body {
    background: #62306d;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 100px;
    background: linear-gradient(90deg, #f7ec7d 70%, #e38f66 70%);
    position: relative;
  }
  div::before,
  div::after {
    content: "";
    position: absolute;
    background: #62306d;
    border-radius: 50%;
    top: -20px;
    left: -20px;
    width: 40px;
    height: 40px;
    box-shadow: 200px 0 #62306d, 200px 100px #62306d, 0 100px #62306d;
  }
  div::after {
    top: -10px;
    left: 130px;
    width: 20px;
    height: 20px;
    box-shadow: 0 100px #62306d;
  }
</style>
```
