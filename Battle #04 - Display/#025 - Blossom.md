# 25 - Boxception

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/25.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body{margin:0;background:#998235;}
  div{
    width:80px;
    heighT:100px;
    background:#1A4341;
    border-radius:0 50px;
    position:absolute;
    left:110px;
    top:60px;
  }
  div:nth-of-type(2){
    border-radius:50px 0;
    left:210px;
    top:140px;
  }
  div:nth-of-type(3){
    width:60px;
    height:80px;
    background:#F3AC3C;
 	left:220px;
    top:50px;
    transform:rotate(90deg)
  }
   div:nth-of-type(4){
    width:60px;
    height:80px;
    background:#F3AC3C;
 	left:120px;
    top:170px;
    transform:rotate(-90deg);
    border-radius:50px 0px;
  }
</style>
```
