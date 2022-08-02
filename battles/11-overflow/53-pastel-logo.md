# Battle #11 - Overflow

## #53 - Pastel Logo

[Link to the problem](https://cssbattle.dev/play/53)

![target](https://cssbattle.dev/targets/53.png)

```html
<div></div>
<style>
  body {
    background: #19191a;
  }
  div {
    width: 75px;
    height: 125px;
    background: #f9e492;
    position: relative;
    top: 117px;
    left: 117px;
  }
  div:after {
    content: "";
    position: absolute;
    top: -75px;
    width: 150px;
    height: 150px;
    background: #dd6b4d;
    border-radius: 50%;
    background: conic-gradient(#4f77ff 180deg, #9ad5ff 180deg 270deg, #4f77ff 270deg);
  }
</style>
```
