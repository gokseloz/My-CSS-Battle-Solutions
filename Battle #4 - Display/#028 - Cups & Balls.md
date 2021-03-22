# 28 - Switches

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/28.png)

## My Solution

```
<div></div><div></div><div></div><div></div>
<div></div><div></div><div></div><div></div>
<style>
  body{margin:0;background:#1A4341;display:flex;align-items:center;flex-wrap:wrap;justify-content:center;padding:80px 50px}
 div {
  	width:50px;
    height:50px;
    background-color:#998235;
    margin:10px;
    border-radius:50%;
  }
  div:nth-of-type(2), div:nth-of-type(3){
    border-radius:50% 50% 0 0;
  }
  div:nth-of-type(2), div:nth-of-type(4), div:nth-of-type(5), div:nth-of-type(7){
    background:#F3AC3C;
  }
  div:nth-of-type(5), div:nth-of-type(8){
    border-radius:0 0 50% 50%;
  }
</style>
```
