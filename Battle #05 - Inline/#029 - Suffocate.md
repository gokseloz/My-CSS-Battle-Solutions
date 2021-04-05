# 29 - Switches

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/29.png)

## My Solution

```
<div>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
</div>
<style>
  body{margin:0; background:#F3AC3C;display:flex;justify-content:center;align-items:center;}
  div {
    width: 200px;
    height: 200px;
    background:#1A4341;
    display:flex;
    flex-wrap:wrap;
  }
  span{
    width:100px;
    height:100px;
    background:#F3AC3C;
    border-radius:0 0 100px 0;
  }
  span:nth-of-type(2){
    border-radius:0 0 0 100px
  }
  span:nth-of-type(3){
    border-radius:0 100px 0 0
  }
  span:nth-of-type(4){
    border-radius:100px 0 0 0
  }
</style>
```
