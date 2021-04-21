# 72 - Sheep

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/72.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body{background:radial-gradient(circle at 47.5% 45%, #6592CF 1.7%, transparent 0%), radial-gradient(circle at 52.5% 45%, #6592CF 1.7%, #243D83 0%)}
  body:before{
    content:"";
    position:absolute;
   	left:170px;
    top:85px;
    left:150px;
    width:60px;
    height:70px;
    background:transparent;
    border:20px solid #6592CF;
    border-radius:50px;
  }
  div{
    width:60px;
    heighT:50px;
    border-radius:50%;
    background:#6592CF;
    position:absolute;
    left:170px;
    top:65px;
    color:#6592CF;
    box-shadow:0 120px;
  }
  div:nth-of-type(2){
    transform:rotate(45deg);
    left:210px;
    top:85px;
    box-shadow:0px 113px;
  }
  div:nth-of-type(3){
    transform:rotate(90deg);
    left:230px;
    top:125px;
    box-shadow:0px 120px;
  }
  div:nth-of-type(4){
    transform:rotate(135deg);
    left:210px;
    top:165px;
    box-shadow:0px 113px
  }
</style>
```
