# Battle #7 - Backface

## #39 - Sunset

[Link to the problem](https://cssbattle.dev/play/39)

![target](https://cssbattle.dev/targets/39.png)

```html
<div></div>
<style>
  body {
    background: #1a4341;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: linear-gradient(#998235 15%, #1a4341 15%, #1a4341 85%, #998235 85%);
    border-radius: 50%;
    display: grid;
    place-items: center;
  }
  div::after {
    content: "";
    position: absolute;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background: linear-gradient(
      transparent 75px,
      #f3ac3c 75px,
      #f3ac3c 95px,
      #1a4341 95px,
      #1a4341 115px,
      #f3ac3c 115px,
      #f3ac3c 135px,
      #1a4341 135px,
      #1a4341 155px,
      #f3ac3c 155px,
      #f3ac3c 175px,
      transparent 175px
    );
  }
</style>
```
