# 44 - Stripes

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/44.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{margin:0;background:#1A4341;display:flex;justify-content:center;align-items:center}
  div {
    width: 180px;
    height: 180px;
    background: repeating-linear-gradient(#F3AC3C 0 20px, #1A4341 20px 40px)
  }
  div:nth-of-type(2){
    position:absolute;
    width:300px;
    height:300px;
    background:#1A4341;
    left:-150px;
    border-radius:50%;
    box-shadow:400px 0 #1A4341;
  }
</style>
```
