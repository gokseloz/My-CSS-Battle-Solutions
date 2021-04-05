# 33 - Birdie

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/33.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{padding-left:25px;background:#1A4341;display:flex;justify-content:center;align-items:center}
  div {
    width: 75px;
    height: 150px;
    background: radial-gradient(circle at 60% 30%, #0B2429 0 13%, #998235 0);
    border-radius:100px 0 0 100px;
  }
  div:nth-of-type(2){
    width:100px;
    height:200;
    border-radius:0 100px 100px 0;
    background:linear-gradient(#F3AC3C 50%, #1A4341 0)
  }
</style>

```
